Thread pool
============
����һ���򵥵��̳߳ص�ʵ�֣�ʹ���˼򵥵��߳�ģ��.


Usage:
============

- ���ȣ�����Ҫ����һ�����ڴ�������ĺ�������


        def do_work(*args, **kwds):
            # do something
        
- ֮����Ϳ��Դ����̳߳أ���ִ��������
    
        from threadpool import ThreadPool
        # Create thread pool with nums threads
        pool = ThreadPool(nums)
        # Add a task into pool
        pool.add_task(do_work, args, kwds)
        # Join and destroy all threads
        pool.destroy()
    
