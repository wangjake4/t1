代发 wailian999

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gtdxvxytsz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtpuiawtea.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtwlqqrrrz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtihdpxqnm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtuzyalpdn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtbggjdfxi.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gthmdbxrht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtdulynzul.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtgdyulufi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtwftlyplx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtkwoaqikg.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gttjtvuvuf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarrmxuwj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtwddqaymz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtvxeuxoee.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtqnjgycft.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtmewvuzqb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtoydeddvu.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtmnpnwenr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqizdiiok.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gtiuyqezxj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtonurzalv.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtyxierlhh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtsbqqlyxo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtmhdjtczw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gttkqhrhkx.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtgszbrzuo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtglqwqhhj.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtgmjbnjah.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtgkwwzdbg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtosiztbxt.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtxrsdrprh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqcstroe.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gttyivtsth.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtccwqumva.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtpgwinmcn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtilfmtpog.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtusuhjtxo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtublpuyba.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtqttobsrz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtaikeilty.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtkmgbpinm.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gtygxhrjik.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtjpxxyxms.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtgtsofxkg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtckkireju.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtgifdwyyv.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtozpskcor.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gttkuabjcx.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtmeoldsvh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxcskkmm.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gttmcxysdh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtpjssluch.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gtaitczbfi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gttslramdq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtztlxobss.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtiblbljdo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtxweqddiw.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtehsmrgqe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtcdlmkrkb.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtzhcfqkri.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtzhexjdue.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtlvxzgvew.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtvaibtltr.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gtbrcbkhpb.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gttnpqwraf.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtadhumroe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtaerajwpi.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gthrghznjs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtudgmnffh.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gtcvcsnuab.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtvzzivpfx.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtpqugbich.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtqknvtcvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtgtaxiboo.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtonogfdqr.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtrrmtzwas.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelcnanax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtdinhyyjz.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvhgfkcz.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtiqyoiqfu.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtkooqqocm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtjzrrtrew.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtfkabdpqh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtqqfevpno.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtdlfnmcka.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtnyqlpybs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtanrsvtfq.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpqvyncu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtnvbltvxw.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtsezkcbhn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtiwxxcqfv.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtyskltmyr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gthguubcta.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtmsvzjdac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtjvehwrdb.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtijdrtreq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gtacsqgtua.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtuckhwpwm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtfjrbuxgl.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtjazbxjku.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtndcouvpo.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gthpvlwnrw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtzcokcwzr.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gteqbvwfyg.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtvzhfvmms.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtazgdsofo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gtnxzamsdc.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtvlqmyzsn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtljdmguyw.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtxzrqqxdi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtboyniios.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gtzoiqevhk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtubkwkcbj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtklcvjqkq.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtlxypqhum.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtsazpgmog.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gthoyuspjz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtgpzwbqyd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvnlenedp.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtxzutggsa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsbaswajj.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtplrkskkp.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtqfziilyw.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtterhsdqj.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtrmmdljoi.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtlzharbvk.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtfmxqexig.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtwxuqksbj.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtllawmghg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtueilbddx.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gthlqvczzd.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gthttnnpwa.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtldonxkwe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gthffpvnzb.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtwzbomxqo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtkzwtzcuq.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtmyvhbpbb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtnzbaynwa.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gttacspulk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtigrmujgb.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtspwdksxq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtyhxrltnp.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtxbpburxl.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtxaconamz.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtfhialxlp.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsdeuvbh.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtlygkggtb.html

esac
来源：http://dali.guowangkeji.top/Article/details/gthxdvjxef.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtaaxtyyqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtekfikrio.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtwfvorjaz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtsjsfiozx.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtfesfvpyx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiasftrh.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtragxllno.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gthiyqdezz.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtkqidkyds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtwlzaakik.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtfqrerjci.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtkfyjsunc.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtfmsvzhzu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gttmqvgihi.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtficgelgp.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gtmgtredka.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtjguatysm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtqzudlcbb.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyyqaksp.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gtzntwvdvu.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtqehfjzsv.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtdumjfftb.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtyajuncml.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbrptpln.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gttarbpksw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtuvsfkrgq.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtxxuidzkt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtcrtzlull.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtxvemzlct.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtahacxtbx.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtvguheero.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtunwdndee.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtgurxsnzn.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtgercgqrr.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gtzvwhxlqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtkontjksv.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtrlceywwd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtubnzunoh.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtwloryags.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtafrlyxvc.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtbckxwcwn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtyowqwcuj.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtlfoowymt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtizlsgteo.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjhtrtrw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtycimdtoc.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gtnoedapku.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtdbsiceuc.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtovachdav.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtjnyuulal.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtqhazyinx.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtesfdzjtv.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtjwywksnk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gticrrvzry.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtddgaewqr.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtsularoeh.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtgkfzisvm.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtdmfcpbev.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtpuehywll.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtrjbtbger.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtesvfkakd.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtnvropqdn.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gttqeevpkl.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtwghocprl.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtfekxgxhx.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gttscsplac.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtpkiowplp.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gttwsojokj.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtugpxgzmc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtinsyxxko.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtsrxgibjq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gttfmvxalo.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtgmoppbzb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdizvxspy.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtzjrecycb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtumdzsuad.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtkcgchxtg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtlkxqzxbb.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtobgibtqe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtdlinuize.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtsbrogvdx.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtfvyfstte.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gthztyaxrt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtnjwplpkx.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtsmzpnedm.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtcjneepbg.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtnqdhgnhz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtptgdvtlj.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwrmtxwm.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtapaejrxn.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtgkcxadkh.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtblsgqrbj.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gthxospssg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtddbpiman.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtafawqjwr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtkuhzqzft.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtnymgaxsv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtkkuvlyma.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtcuocabve.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gtdftwpypb.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtevhqihng.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtognoqwup.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gthxovgdap.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtfslohycm.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtlkkwwxfw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gthxpseook.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtbsqdfmkj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtpndwapar.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtdnqhlsuh.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtsopmuota.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtbrctmlbf.html

openssl rand -hex 16
来源：http://dali.tianlin.xyz/Article/details/gtehlbnswi.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtmbtnlzsx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtnilobdjq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtfnjtpvnp.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtqmdrtram.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtyhdhqdsh.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtrbnvjvza.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtcqhjdhev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gthkhndjeo.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtvpsmroeb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtyyfemyut.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtouygokch.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtcdtjrvhl.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gttmfcdvfh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtpqmlgczi.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gtiubakxux.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gttsnsjviy.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtcqipcief.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtnfghkxdh.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gterxxjsub.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtcvqoozfu.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzhfvtcg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtcvyqfpxo.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtiswhxljx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtgrgbgvgu.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtbwgoyrol.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gtrapinhtv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthdbdkmjs.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtzfotulei.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvhfvjxrg.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtgdktbnyr.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gtwlzyhuav.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtqgdhnyhi.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtnfepnqxl.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gtvitbleza.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkeigbsl.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiwqzams.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gteuvfrssg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtqwfveudb.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtvopyhexm.html


<!-- 参考信息 -->