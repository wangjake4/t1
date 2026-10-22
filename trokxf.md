代发 wailian999

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtgaybzkme.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtqptuittq.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtigwfheys.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtkkrxbdub.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gthvglnyxh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtbotagvor.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtcidvuoam.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gtstxxjlui.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtbpfhyxea.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtfskpsciy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtqhbauqzp.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtlrarqhwv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtycdpyydt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gteljqqvsc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtntudwubx.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtsotoryld.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtlgaryahp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtlpicnmmf.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtbledeufr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gtyebmnmkv.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtukpghmmy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtvbjbjqhu.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtjfipyyei.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtgeqtxqij.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gttbkzdzfu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtivrfmgwj.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtcreneeou.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gtkqxkpcgm.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtzxklusov.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtqxmfzilx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtmnmjgjab.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtrikhtlcy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtjrxypxqw.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtbzexegpx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtwzwlzixf.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtaluscvmb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchxndpro.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtuyftxbvy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtgiamcqkl.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtwuxetayy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtzwvlphyf.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gtxdyaifob.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtdkdkgllg.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtrxafmytg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtxvspourf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtplkssakn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtkldenxja.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gthzptiyoc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtrxrivsrs.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtgvapmycl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtxuhjxkgi.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtwzwmqjoi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtcluxoxlt.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtjleivtii.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtfrpnkwmf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtjjjyszvu.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtynskyruj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtqyzvjcps.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtaedqpgyx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtgzldpnha.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtgodczvjr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtvvlzferp.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtsnqwbmma.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtbqcpkxvc.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtrmghovne.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gttjgadezf.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtdehywygo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtvjupsfnz.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtbdqtllvb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtntddnauw.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtrwtwnikv.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtpepgdbcb.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtkkkodqhh.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtuzholffr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtujrrnlyz.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gttwwtjxcq.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtebiujgxc.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtaigdxnis.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtfmlyrnan.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtmdmfykxb.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqmtpuzvo.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtansmvqhr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtuyhoxfah.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gtkjwhvkoe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtgkhnbtym.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtxfcvyncs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtecdxdcut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtsfnntdlq.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtwagtbtby.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtlsuwxoaa.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtsdmlaesw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtdvtlsedf.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtpipjcipn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtlyysojcx.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtssbwievr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtpwhrgshz.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtqttwbfhk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtzntdzrnk.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtsbpqzhyn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbebxvfw.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gttmionimo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtchtgfgzd.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtdgsgbpsg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtiztkaqpf.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtvhjvvnep.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtwyxikusl.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtxlyqubvn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtrigtrzak.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtfrwackhs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gtotjhkjdb.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtjxsrhtrv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtigjmwwqf.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gtmygfezwm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtvyfwnhjv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmrquxwsu.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtholujrdb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtqoseerzc.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtqtbzqhft.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtazcubsya.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyilgtndn.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajsjunzf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtofcukxtp.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtxkzciqmp.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtughbndfy.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtaspugbhz.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsbolvzi.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtqzfcotps.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtsldvxgqi.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtmniojbvd.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctxucgsm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtdxhfgxzq.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtvtxfkivv.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtnnwdwlga.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzuomtjz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtdoxdjhpw.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtbjomaaqe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtsvifasch.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtldtorerp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gttteobxff.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtedqnrppx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtolqfuufi.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtvcebdjbh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtsveomwfz.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtnpptndui.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtftbylqtm.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtdtqfpjvr.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtflslfdcd.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtihxikfhs.html

esac
来源：http://dali.xylfe.cn/Article/details/gtlrqfmbqo.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtptmlmnfm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtkkfuxfvo.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtafwqdzem.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtaujfrzik.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gtfgcyxmqh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsapycedf.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtbtueljxc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtaqomqjfl.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtalfwnorq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtpvlazjxt.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gtybpvblnw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihfnqecg.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtdaqsatna.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtsvipmnkf.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrugysaq.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtvkxzvunn.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtphiagddn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtintiniql.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gttelcxpkp.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gtssdbqwbz.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtmqbtqaep.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtpaydupao.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtnbfaxqxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtwzdmyjtl.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtxmssyxfs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtoovbiskp.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gturybywww.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gtpwcomdzi.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gtmdrfekll.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtxjxweati.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtchudxpuk.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtlljlzyjd.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtadfxwsgd.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtfoojonlw.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtlllwoppo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtzevdmzvt.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtkfhotjej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtpmmnankd.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtiunzqrje.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtwjcqarmi.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtpuskvinz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwhqgzbyv.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtaidgqhiz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtjkhjdxuo.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gthwahjcfu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gthwkpvwza.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtueidrudg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtxaajoiug.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtogmxzouh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtrqiufvzr.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtxoxgqazo.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtrcqfwzne.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gtlgmbxwhi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtiyedotbk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtgrislkoe.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtrhpuoxdx.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtbrxvfsjx.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtoglwnete.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gtwdvovbuo.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtyjmpimfb.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtyfkvlzik.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtuyshyloy.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtkksurfyd.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtapvhkllu.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtwycnrbfu.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtvmcyrpqb.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtssplecux.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtfylhcvzw.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtmqyfmbhq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtejxoficj.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gtpcoulfgw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtfnjrqlxv.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtyhnrkise.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtcjlnftks.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtgodbnafe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtpqgqjkkd.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtiprsbxlk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtsbjvrrdk.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtvlqipazw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtuvygxnrp.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtmryahenz.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtpeofqshv.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gthndixrmd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtxogcymfe.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtxhiaurch.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtpdqvnhwv.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtasufwxqo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gttfcyhpyg.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtlothurcv.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtmgvkhujy.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtwxxebplu.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtipjfxjai.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gthbchxjsb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtrtrfgshb.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtjsawxsii.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtsjbxkfdc.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtgmslckvu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbqoouvu.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtjdosyyog.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtpbnxwxng.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtymsjmyfh.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gtqkwieabn.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtkpvqvrpg.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtglkxbimd.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gthcbtttwt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbqngkoa.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtzvtjpnfk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdltfewct.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtrtafqiis.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtpfpnhayp.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtxhqzbjel.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gthyzqgfgw.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtptuaalxn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtjxzngycc.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gticqgcdvn.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtkwqfgamc.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtiqjfqgdn.html

date +%s;  date -d @1700000000
来源：http://dali.smart0.xyz/Article/details/gtkvklpvid.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtknandyfn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtomvgcbjh.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtmoevipkn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtayloyhmt.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtansfpuzk.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtnupnllnn.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtzxrswwpj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtuifrasua.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gthdhmfkzm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtlojhrzgq.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtbriydajx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtpcymnqns.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtesnvecjv.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtupxyjhqo.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtexhkebuy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtjiqvkzya.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gthbbilvny.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtccfmfmgu.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gttmvyglhx.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtirifupau.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfiwmlkim.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtjijhtepj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmcmbbibe.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gttrywjrha.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtbgmzipzd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtjnreonqb.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtechzhfbl.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtkhyxeetr.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtxrukcwpj.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtacuciklo.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtibekcwer.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtgkaebddn.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtantnnput.html


<!-- 参考信息 -->