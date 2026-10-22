代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gthtlkiheo.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtqxciwemi.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtesuubnwa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjlciryk.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtqtyvzxlw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtrxrtwutp.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthnjlauq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtkhgsbjhf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gtvesboyeg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtiqkuerhl.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtjasxwioa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtzeteidqc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprraeuoa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gtsmqtjrjq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gtoomzypjs.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtocraubag.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gthasiwaab.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtsurvrkqu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtnjavqzkm.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtmaesnsul.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtbbdtjzvz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtikjkxbvd.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gthitfbtde.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtagqbnvcm.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtokiktwlc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtzyfecviw.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtjhfnxfvm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtrsioswbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gttztpgxxx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtevwuiynj.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtdjbuapkg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtjvtwkhiq.html

[Q48] CTE 公用表表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtssasttlf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtvxpsblbm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtjimdopqh.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtodxvomgm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrrocaep.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gteircerrb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtbqqcbrno.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gthjbmskie.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtcvqudtgu.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtjmwjqztq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtfzxpfuoj.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfyprvrl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtcovuqzcn.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtffdieiom.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtaskdxvtd.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtwjtaxybv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtpawbllaw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtjpwwyaze.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtlqlgysrd.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwobkeoli.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtaombupne.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtraoghbua.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtdfqjvvwu.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtmzgdiccd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtnqrutppr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcpngspr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtxtlxstna.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtgxomkqkl.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajrwkjec.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtdjqwdvro.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtkxdyhdam.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtiqgtarjf.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmmqyjac.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtaqouzvqw.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtghbmoume.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtqqsojrvm.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtvhkmbhgl.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gtfibsjggz.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtfleniksi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtgzevykbe.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavnjqmvz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtofknvmrv.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtqjkzddsh.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gthzxtxino.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtsftvbgjo.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtfdftxqvw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtvnilqirh.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtilyxgszo.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmqokuml.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtxhmatmjg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtzqonsmio.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtaiuwwhef.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtsryiqjfv.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtnnyjgtmf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtzvrtboqb.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtvrqzowwl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjjxlqwf.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtzowlgjvc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtrwzatnwv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtamlwkwtv.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtaoxvubrb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtfhuslnal.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtqbwfotne.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gtpmvbhdkf.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtutfssvva.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtsdygvabi.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtljznyirz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtueeeqxgz.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtgahcacte.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtybaueesy.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtmammarvv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtuwjijuue.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtgseyzfzj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtghnthlvc.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtlugnbdeo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdcpxetoz.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtbaxgubik.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtlporwzxx.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gttqfkiisl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtdlzxhgrl.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtpmmgwaqo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtoigpepyu.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtwejlylqa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gturlftdyn.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtfzlelzpp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtwodktnzk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtomezouvw.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gttdwtmbti.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtbixksrzj.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtikrstkhp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gtyswxcrwe.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjgaavsif.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gtimmkxhrr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzrcmlolg.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtanlepnkg.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtmcyvjugq.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtrbapxqgn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtfeapeeku.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtrudjxckt.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtrlhueyrf.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtdcyzbdxr.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtwrchigng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtjtfzxdkw.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gtbhizsrle.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtldxjowih.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxdrvkes.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtlbtmdyhw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtnjrtqgfs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtqzmxkbul.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtvmlulhuz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtbhcghzzo.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnzdakrm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtwvqtnyjf.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gtlbffgrei.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtgybgzyjn.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtwxwjovyz.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtaowjdynw.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoggwldo.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtfdiotxem.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtctdrfant.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtaofvdjex.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtfedyumyu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtsvdtuzad.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtiliqtoie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtagtbnceq.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtvnieavij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnedfhbhk.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtruejpfgc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtxtedyuzd.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gtnbhhtonw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtwnmcbdfg.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlprqrscv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtlxoxappw.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtxdoglupa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtsjqesebv.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtwrjzvhtu.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtxgchoegx.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtvlsfffgc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtfkmhtvbd.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtzngqvgvu.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtnddnevqf.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtvujjhgqb.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcenbbnm.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtplupvzgu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtidohsjdn.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtujtmiwlr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtoyqotzse.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtmptlgypr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtpjjiuldd.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtsdyvlmzn.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtggzwzbol.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtubmchkax.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtrmfhxvan.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gthkwlaasq.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtrshibytd.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtkwfyzxyv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gtmxlkeibs.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnbjzgls.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtnrgqrjfu.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtrmghaonp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtsdnscvea.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtdbpcjgjn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtbivbnnfm.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtsbnwdasv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtcrgwquub.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtkcishcsa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gthsworqri.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtldkupxla.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtxdwfblyr.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtfzvvnjbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtdzdehzwq.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtdnfwxyws.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtksvcbkpr.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gtvqmngmxa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtymrcmlun.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtftijxnhf.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtobatmbii.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtpwnyxgpr.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtvokjpufx.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtfpwihvvv.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveqwrwdc.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtvdftvsdn.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtvdvbsbin.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtsuvsqxbc.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtapzhdoox.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtgtpmhrzo.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtkxkcatcs.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gttzxuabgq.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtxmtzjvjo.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtojrcnviy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtpdklekhx.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtwyylmiwm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtlbwtocfv.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtixcfoitl.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtvbafclty.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtjdpohccp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gtneyysija.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtyaocbrst.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtiytqzjig.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtudceovag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtcmeqxcon.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gttympewwk.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtzykeduqq.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtxjrzcrbz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtexptgwne.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gthmkiubuu.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gttqxheyga.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtfbrcrvgz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtltchlkai.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtxcmfvyor.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtjfujbihj.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtpmsqugxk.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtwfylpegk.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gtvzwsaesg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtfnmxcokm.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gthyduolqm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtjduqdlkx.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtktgbtoxo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtwmssqera.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtydimugpk.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtewiwteve.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqezgkux.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtcgvbvngo.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtadulmmza.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtuagaihqs.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtdvmktiqa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtbjedonoa.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuybxfryn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtjwakvzex.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtocgqltla.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusnopers.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtcpnsdjhr.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtezpfracq.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtbjnfvkwb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtvhqwjvmc.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtkqssxtew.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gttpolwcfi.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtqreknlhk.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gthnjvbggk.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtuyyelmtr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtoezwneye.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gtnsyoeqwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtirnrnbos.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtnjqrtinc.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gteemkxles.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtcypnpiga.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtcfiqdeec.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtjwsdtbeu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gteguocnzv.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfqzvyugt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtorjkesvd.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtopdfhsas.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtaehbdsyn.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtawucbzyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gtqraiycgp.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtvmqflirr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtbhckrzsp.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtdhopwqjj.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtudeqswda.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmfglgtmo.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtiqtlgxgo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrwsascmf.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtflkxnbew.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gthzeinsej.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtpwlkykfg.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtxnpwtfjh.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtulyurvmn.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtdbqimhtf.html


<!-- 参考信息 -->