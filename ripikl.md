代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2jrsbvakj.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gt2simsdscn.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2svjyhtsz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2ljdjqdxe.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzhqihod.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2nlmqzmyk.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gt2bstrknaq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2mllyhskd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gt2baqguovk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2xuqjavnb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gt2tzbtqfho.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2znfcwwix.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2smsngvxn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2zzuvhsjt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2vcqlxitm.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gt2vxaopnmg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2hhxplipi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gt2dwlrolmy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2yquevpgk.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gt2asrgxizn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gt2auqpkscx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gt2bniwutyl.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gt2mmmnxhnz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gt2orzipmrn.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2nzqpiemt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2bemvjkbt.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gt2zhrxpdgi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2cvulmzcz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2jnuwdzvl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmptupjb.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2cpeoggyk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gt2sxnxwgvh.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2otofodey.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gt2nrsaqaky.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2ipmsxdld.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2lazukbyh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2dulhheue.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txeylfuj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2xlzupajl.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gt2ltuuifrn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2inxzvrhc.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gt2avuehlbd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2ndwekmdd.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gt2yhhjnusg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2zelmlfkd.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cppixdtc.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2sdhciyji.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2iqtloyjm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2uvhogjvr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gt2yvpenztx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2sihxssfe.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gt2wnbpybps.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2xkczrkxo.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2ffqqicyt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2fnjmytld.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gt2pbgcnnrl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2wvnzatpy.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmuzspcb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvlgfwzh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvppdimj.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2qmjkpdvi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2bkzmipbi.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gt2tkiihmtj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2wblgxjls.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gt2zbvdstal.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2thgcqxxg.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gt2vlnupbob.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2pvtyxjfo.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2eujobuff.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gt2ipocfxka.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gt2jdkmfmtp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2ltpxmclp.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2bbkpzvhk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gt2sikyvnzl.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gt2zrhclagi.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwpculpp.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2pzxcdeyz.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gt2olpiyekx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gt2yktinmbm.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2alknnaso.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xoyolnvn.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2buyuetbc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2slinsglt.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gt2gmwfgora.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptcbwhgn.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gt2mitxqpzn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gt2kugkbwzk.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gt2uhgvzfiv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gt2mfwrgrzi.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2ybjjbusm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2rknurgvg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gt2vrnixjqt.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gt2ueenlyhc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2byvwcadf.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzktifcj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gt2pdguaowz.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpxyyzwp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2hryhudac.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2emhzrgzq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2dqjmflpn.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gt2ycdqomhc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2edxpvtdc.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgymxcwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2lxlmtqzc.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2fdgjftgc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2jwcwnuqn.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2rqdnfflt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2zkurmqdn.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gt2mruwmlbp.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2ytitjhhl.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gt2wlqojjnf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuffmzzj.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2gypgommb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2ohjgqnmq.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2tjnibrzs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2gajukrkv.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2snhtccsv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gt2vjcjcvca.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ortfpsvv.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gt2hmuybtlb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gt2lmacpeww.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gt2xvgfyngs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2tdowbuuo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2trgtkogt.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2tseuqneo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ihiknfho.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaewvoby.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2issdvtit.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2otchezxr.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gt2ligvhjox.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2clrczxwa.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gt2qtynpzyp.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gt2cyqpzvqi.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gt2ljcwgpwm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2pmztawqs.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2csxrrrqw.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlyhbutj.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2bxyguepi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2pvcposez.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2wdujtarf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2cbaymwpm.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2slxelppp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbtdxntd.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2enuiwsiv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2nlwvhjuh.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gt2exrrgcea.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2bkjlzmfa.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvbvyucv.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyygpzqq.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2hvnprxau.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2nbgghbsc.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2zqgtvfhj.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2idcllzlp.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2ufwghceo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2zwuuejwx.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyvdvbio.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2mlxkforl.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbbpjcsp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2oldcmugp.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ontxskuj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2gsejfatn.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2tlfpwawe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2rmhvemez.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gt2yofohmbd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gt2fwbctulz.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gt2lhjadjbh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gt2jbwkpvbi.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2npedzslz.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gt2gvbetccz.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2rkjpofnd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gt2pllsrtqv.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2qfdzvnye.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gt2keogmjfc.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2wddjcldr.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2hlpkaqbm.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2quoxpfva.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gt2ellfivkw.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2thinuvlk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gt2hovuchye.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2jofbkxax.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gt2flyzjnvv.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gt2rmufoboj.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2pkzrhhpb.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gt2bsgpwtgl.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2vebmheiw.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2ydsopvon.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gt2dqatiuwf.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2ztdhifdy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2tvsxdyur.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gt2sfpweycl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gt2psnadyqp.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpadvkkp.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gt2hjhcesoa.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gt2mkdykwqz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gt2usnytpvi.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2yibxgxbs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gt2imcuqxal.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gt2drmzrsaa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2altozvbn.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2rsgmlezw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gt2pndmnrku.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2urnddjro.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gt2ncuoegwg.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2xgjfclxm.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gt2tgfxtgjn.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pamjzvbw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gt2vpfujptt.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gt2kskhntyo.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gt2lyhhhnbp.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2humaruia.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gt2mujmctrk.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gt2kaodmddo.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2ndgnptea.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2kzzrhjwm.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olnzemah.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqzuskpg.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gt2xvzudxcd.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2moqfqlzk.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2seiagmmj.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2lbwyusig.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2qbwsadbw.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gt2qtxmdfqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2yzghyjbz.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2tvwwkxyc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2rbryjkgr.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2vpjvdwxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2sndrezuj.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gt2rrtagsgv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gt2picyxwfk.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2bighxkyj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2kgznwpmm.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gt2gcyecetr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2pvxypfuf.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2iqvytcqn.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbskjbst.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2xiqoouka.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gt2bupwvmpg.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2dnthwgvj.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gt2uatpfqrp.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gt2ibutbtpb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gt2pcguxwvf.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gt2hxudjvxb.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gt2jljrtrzr.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2kmfyjsxd.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2badrcsla.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gt2jguoaqvj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2pibupzlg.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebuguddn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2knetmugb.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2jolchpot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gt2hjsgtvoy.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2fkxrpkda.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gt2mwqlikef.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gt2xrjpmsfr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gt2qlayxtim.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgfzkzua.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gt2vnctovmx.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2ugjzkeqm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gt2kajgnktq.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gt2ggwpjmvz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2ejzkrvfh.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gt2cansmfxn.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2tfnntqsf.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gt2tliknezi.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gt2sorvgonp.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gt2cwfbbcnp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2mjhdsezy.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gt2vygziawa.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvzmoyjh.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2eufyfegm.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gt2fnywbjdb.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2hfczupjz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2ujsrorou.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2rnovwvob.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2bollncnb.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aojpvzvo.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gt2gazywdma.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiotrjtp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gt2zolwzkgl.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gt2jltwjsjd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2ttpwdfzh.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gt2oeexxcpk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2swhvcstu.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2corxnxvh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzjkoos.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2lhdcnbor.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gt2dtdvrsbh.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2dowztvhi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gt2dagycizz.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gt2xlwcjhjd.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2qafwjcdw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2wmuxomnl.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gt2tqlhbmmv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vnejbvvw.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2algbtnhe.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2eivhgaqp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gt2qkbtejun.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gt2kcujqcvt.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gt2mnlijlbp.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gt2yjcozglv.html


<!-- 参考信息 -->