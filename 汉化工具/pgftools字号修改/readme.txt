
PGF tools v0.5 by tpu
---------------------

PGF���߰����ڴ�����༭PSP��ϵͳ�ֿ⣬������XMB�Լ���Ϸ�У��ṩ���õ����顣



ʹ��˵��
--------

dump_pgf.exe
    ������ʾpgf�ֿ�ĸ�����Ϣ��

    dump_pgf [-h] [-m] [-c] [-i] [-s] [-p] [-b] {pgf file}

      -h: ����ͷ��Ϣ
      -m: ����ߴ���Ϣ��
      -c: �������������ַ���unicode�б�
      -i: ÿ���ַ�����Ϣ
      -s: ��������Ӱ��Ϣ���ַ��б�
      -p: �ַ����ļ��е�ָ���
      -b: ȫ���ַ���λͼ��ÿҳ256���ַ�

    ���У�-cѡ�����ɵ��б��������ں��������ߡ�

mix_pgf.exe
    �������pgf������ַ�

    mix_pgf <target.pgf> <source.pgf>
    ��<source.pgf>�е��ַ��滻<target.pgf>�е���ͬ�ַ���
    �������xxx.pgf.txt�б��ļ����������xxx.pgf.txt�б����xxx.pgf�е��ַ���������������pgf�ֿ⡣

ttf_pgf.exe
    ��TTF�ֿ�����PGF�ֿ�

    ttf_pgf {xxx.ttf} {out.pgf} [unicode list]
    ����xxx.ttf�е��ַ�������Ϊout.pgf��
    ���ָ��һ��unicode�б��ļ����򲻼�������TTF�ֿ⣬ֻ�����б��е��ַ���


һЩ����
--------
    dump_pgf -c jpn0.pgf > list_jpn0.txt
    ȡ��ϵͳ����jpn0.pgf��ȫ���ַ��б�

    dump_pgf -b jpn0.pgf
    ��jpn0.pgf�е�ȫ���֣���ҳת��Ϊbmpͼ����ŵ�Ŀ¼jpn0_bmp�С�

    ttf_pgf msyh.ttf new_jpn0.pgf list_jpn0.txt
    ���ź����壬��������jpn0.pgf

    mix_pgf new_jpn0.pgf ltn0.pgf
    ��ltn0.pgf�е��ַ����滻new_jpn0.pgf�е�Ӣ���ַ���


��л
----

skylark@mips.for.ever
�����������PGF�������ߣ���Ȼֻ֧��Ӣ��

BenHur - http://www.psp-programming.com/benhur
��PGF��ʽ��������ϸ������

