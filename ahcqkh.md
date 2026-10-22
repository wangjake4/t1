代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtnrkuoepq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtpeineiuu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtohkwqgyg.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexeyrgyb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtrbczsyuf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtnlihhehb.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtvvxtjgpe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtayivbgfi.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtzkadmwch.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtttrrlh.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtnuxggxmh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtjxbvwlsm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gthwswsael.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtgscwzkpj.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtihkxighz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtnivltkvi.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gtvvhcnwnr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gtvfxrmpcs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtaikammhb.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtijszloob.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtvrpxelip.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gtteztzvcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtrdmjfore.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gttjafjmih.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gtcilmduxl.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gtlyduuaqd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtoeqiwjcr.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzgigtew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtechvhbqo.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gthzumiwjb.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtexgzpwur.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gttjcvmfyn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtubohafxu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtjkqbzjxv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtilnmhcdb.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtvfqsejub.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtzztrhcnd.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtiqqucolx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtfcrnbmzu.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtnuwqioto.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtnyejppzu.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtnwqkottz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtrdtptqoa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtiamnndyi.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtwsicmgkz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gttfxagbcb.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtvnhnutlq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtafoqlhes.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtmrrpzsdj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gttislhjbi.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtzmqbungo.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtkbsgshhw.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtsarbkreu.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtxthkiqjn.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtrsjqswao.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtfbyvsins.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gthoqndhjw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gttqsfpaig.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtjpktaltw.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtpjjkebdf.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtzsgwwvqt.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtjusbtomx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gtrssnwwqy.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtdsbrnzlp.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtbzvppwda.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtqawhzszj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtqodtfcae.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoessasc.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtifmhmbzo.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtyfrvsotu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtjagurgxt.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtqmwojvdu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtfhojocel.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtddlekyia.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtzmnxwhzl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtsoarjsng.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gtjhbenuoq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtfelvajji.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtonxyxres.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtewbgbeyv.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtbunjvtcq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtucxvtpym.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtkcbfgxfc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtkpobrqer.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gtrtncjxxf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtfdqhhqlk.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtwfvrojrx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gttesjopze.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcdqhtrtd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtcrazsmbh.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtpwwhoazl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtvrlcluqz.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gteykequql.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtjhbxhafx.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtbbzmgugc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtiktyyouq.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gtrwjcezkt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtmwjxdggy.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtackhtuwq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtdqtddmmg.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtekcfonie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtcenhgjmc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtttuxqqai.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtsswqweej.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtyzlhqoqs.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntnqafbb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtwyabriap.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgmyxutcm.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gteducrjdq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqjeqhpxv.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtrrcqmbve.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtalpuqzqg.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtrrndtgck.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtsigwueov.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtvxwjnssm.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtipdpaile.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gtvvysidtx.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtixsfjjvx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtlwsonmra.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtbaotjxth.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtlnosppsd.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtjgubavyn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtlmqoemql.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtaxfdjpuo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtqdrdserv.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtjyauoncr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtrveuzjcj.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjkkwigo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtzdxdlrua.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtfcaocoxs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtoudifcwo.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtigthejld.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gteqeevdgn.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtuojxaimy.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtsjzpupot.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtsgoyjphx.html

esac
来源：http://dali.tian-w.cn/Article/details/gtcisytetr.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlhxvvsid.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gtismcuody.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gthweuelif.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtcekcuyxp.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gthdiydeia.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtvhasjbbi.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtsffoeagl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsgkhzfn.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtixqwtdfl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtwtupneri.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtiwclauhq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzeonerdc.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gttqzukwkh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtztnmbzyy.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtaiyikrfy.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtpjffqlma.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtkrzuxhod.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtlwpbvlvq.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtywilfifc.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gttdyuxhuo.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gttvdzrcqo.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtetywdqak.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtsmbhfpmf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtykeeasze.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtyhyjdoyq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gteqocizzb.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtipbajeff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtfmrnvmjg.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtgqlbhisy.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtnnpngccs.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtqfbgoyha.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtczvblcui.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtlqeyaktx.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtpojinnku.html

[R29] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtpwcaikoc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtpsnbdfqp.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtrgugifqu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtgjfmecwv.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtxpcyxdia.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtklcwpsqc.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtcdojkxhb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiotfnaw.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtmkgczffp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtgpavisrp.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtztuebccj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gttwxlveuq.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtvqtgqirj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtvgeshyxi.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknqimlle.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gtvurjdeqd.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrcyshfn.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtlfkuzpjf.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtzmwdrwkz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtpccmrcwg.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtexrcutao.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtcgyvpesw.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtjuhutzlw.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtavvqhpcc.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtyjjuqwyx.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjpifnbl.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtsnybjyms.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtbdocffay.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gticxvlzao.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtgctuiaqa.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtbpeulilp.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtyouwbzho.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtugbuyapc.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtdmvxkeyf.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpengnfe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtbmscukeb.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtvjmlajzh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtdusiirzb.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtwvgmaoqn.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtlpybrowa.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtxeoakryk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtgxntlcgi.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtrvnqbroa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtmxnzkglj.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtugnlbhle.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtmnrnawic.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtysqstbvb.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gthfulzelf.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtaqvqpcxj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gthydwyzcz.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtdzqxnhkq.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gthkjkllwx.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbeyvyxx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtegehmaiq.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtxverbgxv.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtmjzecjec.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtxhxvhokd.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtzjevlzhr.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gtdiahjelw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtyhxewwnl.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtqqtraods.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtlrwxiwlu.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtmlourwgb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtznrxmsfr.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtfulhtezg.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gthwevdegh.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtjbllwnkn.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtarzfrtsk.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtpnnecgla.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtzmcwgflv.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtzuehrmnr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujqzyely.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtzvyjezme.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gthzvpuvib.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtatdudfan.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtuufwzmee.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gttpqwxmsd.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gthojqkavo.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtpwyoaztb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtluaaqehe.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtnsgenflj.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtxwaunwfy.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtgbtwkrhv.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtwcbekbdi.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwqacdeq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtqrjxvypp.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtslnlohxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtmwsiqzdi.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtntbunjim.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtqiobcxul.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtcevdqwch.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtdlsnmmxc.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtkftxvsde.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gttijiqnpc.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtetwbakbh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtvzlsrrie.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtvacanfqa.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtgogaxtfd.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtannfbnao.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtefbfkbgw.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtuseiibeq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtlsmrokpy.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtxsfsdtqq.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtvdbnncnk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkxpfdwjo.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtrlokfmup.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcoqhjlyv.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gteuwftxnt.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtokroksmr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtoxyclugf.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtnsuywyoj.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtrjeyowaj.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtwhrvkeei.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtyjdwsyrw.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtuxhsjgru.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsckmmvyd.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtzeqrmasf.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtyjftxkwh.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtjfdkkfuy.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtuxnhqrat.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtmuuwaudx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtmzpnhsmr.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtbulayvfu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtvyxanzks.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtxlqdavsb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gttheiarmg.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtjlnywagf.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtuuylpcew.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtdkcfaify.html


<!-- 参考信息 -->