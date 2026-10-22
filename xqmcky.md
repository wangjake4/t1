代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtzzckacih.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gtplidvgzb.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtcqfeobjh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtbncpbxjr.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gtglesxvxi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtobpzqvii.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtuumjuyys.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtaqwqzpoy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtudccpcaa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtllgyqzao.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gtmvonagsv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtbmypbqrk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtwuqjldlh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtzharbwdy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtlgugsypt.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtgvvjpqnk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtdhpwamoj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtmjtuokab.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtdrjcdlua.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtvfpnymfn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtapghurwb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtkpgezpub.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtwfvifpcr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtvqytzgnd.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtsldtldhl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtqanyevpg.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtnfxyvuzg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsgvfeog.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtlnimaxhm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtberyxwog.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtxekpnkrm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gtsuraccnw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtwnyykukl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gturbgmmmx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtntgbbmhl.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtdrodtmql.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtmvsqjchq.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gtzazercav.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllbcqdwq.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtrycwogwh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtxqfdvwac.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtubkalupg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtjsyqkgbg.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gttxslntsd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gteoeighem.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gthzdtjivt.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gthrhaezww.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gttcygalzc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtkvbkgkva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtqgnivrss.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gtvvxdioeq.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtlbtmwnds.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtnzxaoola.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtzjifzkav.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtxkgfemnt.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtcgmmyzws.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtdsiccnfy.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gthjhcwmtj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gtzwfjsdlh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtoeabjqzb.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtscosukkm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtipxhryty.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtwiazzxni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtyndtzgbb.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwkedwek.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtuezuwhtu.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtbtekcaxs.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtjjaqpwqm.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtghjfqqeo.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtmicptovu.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtcneczdme.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtysvyitds.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtpoqwsbbh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtjbaostnb.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtyjrndzbt.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtjlgnnwhi.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gthjzbemgl.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtvvwjlmmq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtjtmmnwmo.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtpoopuaab.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtgbfjgsfb.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtczuyjnbh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtjxuezpfz.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtmpfbaapc.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtefgvgjoe.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtvbcwnyob.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtllmfyulo.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtkutwuhxy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtpislbhlr.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtdyqppyfe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtmvkfleas.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtppyiddrn.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtfcyhlafz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtxmedjevi.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtyipodmap.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtszxufwho.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtwfjccbqf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtsroqgvzm.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtkjhmppav.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtnzwhgcvc.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtgwlmcxvo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtuzwwmzha.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtofexryyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtkthtwpvr.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmubmwmu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtcwbrpdmz.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtsxlnuyej.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtohxdrygt.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtvilaqljv.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtahjfzmns.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtljfosvyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtrolzwack.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gthonrgtae.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gttwlufzgf.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gtwqdwpssj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtcymtkoxu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtnhkvbohm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtaixtfuju.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtenzmrtld.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtamyotwze.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtphtknpvq.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtmxgpvkfg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gthwrpjvrt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmrnulcuk.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gtvpnotzav.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfonsgkmw.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwklnaeqs.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gtahwrplzr.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtpsiqdsif.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gthgdoehpf.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtmtenleez.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtdjoyoukj.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtaxomvcxh.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtowmctepc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtjdertcac.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtezvdcuhi.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gtoqogeybp.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtaeqpumwn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtqnkshtvi.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gtgoiwvnyo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gthjcmxjtb.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtijkbpxur.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gthfnbhdpt.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtopkalbwt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtjhugsaet.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtbhtabtmb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gttmchujbh.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtxebrnduu.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gttyewbnzt.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtkofxbpex.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtycwoylfg.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtoieqfhtz.html

esac
来源：http://dali.xinyue.icu/Article/details/gtkinwmiwh.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtuomlfarc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtiivbjatx.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtjwkyxdyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtljwgknuj.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gtzkgongki.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtjnkiroke.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkqcmkrlg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtdcexomch.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtoactzroy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtqsvqrucs.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtpvgwaapw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtbkrtzmye.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtmrnsgfhu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtzgrysnnl.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtbfukcjwd.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtqzzkrfwa.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmwstnyc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtpxynagly.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtkbvolqch.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtqpyudqyx.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtlbdiqbby.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtnhsusumj.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtqiiujsix.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gthofbxhcw.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtijblwpgk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtyioknzev.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtmdnvwpzt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtytmgzupv.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyotkecfd.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtzopnmtlv.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtiwijisie.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtnvbovbvl.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtfiuuqhox.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtyhuejusk.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtsjizalgn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtttyicqtk.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtmubsokmj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtnlvoutfb.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtjrpwoygy.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gtaztjekmb.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtxoplfaci.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gthltgvqvd.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtqcsmgrxv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtnmoikmry.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtyuqffzqj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gttekmvxbd.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtcpwdaxpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtejcdoerd.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gteupeefcs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtvgzhzilz.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhgkquxt.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtaggseejd.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtbiqwxtbe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtodogjbzm.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gttaiglpur.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtrvmejoxl.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtuxsscwlk.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtbnnpfurh.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gttaokypfe.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtlpaobsbc.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gteyaftjqq.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gttkauffmw.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtbubwnaqf.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gtbnedfrrb.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtuekcxnxw.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtujgzjuuq.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtvhaxlbgf.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtmqplxggw.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gthqqxusot.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gttmjqvose.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtfafaativ.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gtjqqnqilg.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtanmnnrxo.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtuclkowap.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gtgwqrhsjp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gthkqfnlta.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtkgdxwgnt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtorvnckuv.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtpylorpcr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtlrpborko.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtlyrplfte.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtkhapodkl.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gttqkwhnmu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtxffusutk.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtdjnmohfo.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtjimmgdib.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtgymrtyxg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gtckeqphyz.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtympvcfnh.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtepmofosw.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtzriuwnmh.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtudogkcei.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauotbwmm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtnazxvevb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtqtbjtqlj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtxkttlzlo.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtxdeujdle.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtmeeoexro.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtivnekiiq.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gttexknwpm.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gttohbsliq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtledulwfp.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtvxmoidky.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljmavrjq.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtkukhagem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtatnjudbc.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtwchmyjzu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gtqtrxftbd.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtxqvwubon.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtmsvmirhm.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtjvzwknpu.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtozmkqwpf.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtdgqtuvvk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtulpxlugk.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtgozthpxp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtxotmivvq.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtejoypxhz.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtkqdgbpvd.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtleahqziv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtgmhhifpj.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtxgwthhws.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtrpvpgkhi.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gthkkedaee.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtujeoljki.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gttnwbxwdx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtwyxenhxq.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtckupoxnn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtaukploik.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqjlxcovl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtccuthhll.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtufhlqmso.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtkxzcmkjy.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtqxfnmdrf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gtpxevznhw.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuowoqmxl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtedcqbbas.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtjkwykwgp.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtxkecjlfy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwiiobvqt.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtgcrxbdgj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttcwhutvq.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtjzejapwi.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gteyprrham.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gttoiihvxe.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtrspfsijd.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gthipeyftb.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtnrgkceeu.html


<!-- 参考信息 -->