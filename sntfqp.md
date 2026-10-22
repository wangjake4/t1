代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2vmzzhpls.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esgimmwz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzljglxc.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gt2yrtdissk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2zrjmypsa.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2xjthjgzh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2ujrcbkiu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2blytnrzw.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gt2hrwkyrnh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2ieiqecqt.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gt2ntvbiuhw.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gt2xykevgyy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gt2fujuzrmi.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbyuyoub.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2yisfwazv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2qbpgkucy.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2sukjixym.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2hfeyvonm.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gt2ynqmvtym.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2silumicu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gt2cimahgun.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gt2eyerjhtm.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gt2amnvalkx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gt2orixncid.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gt2ikkmnwdm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2ulgssywt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gt2kdxskiqi.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2sexlrarj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2pgvyzvkc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gt2wmddkrde.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gt2lydeadei.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gt2weuqnfii.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2pwgmttle.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2ylltbzsb.html

[Q43] 标量子查询
来源：http://dali.jqgufenzy.top/Article/details/gt2rqrkosog.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gt2vbexxeta.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gt2uelfdnbe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gt2nyzotxpm.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjrnhpfr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2eowekpbq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gt2kotvyclq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2qrbmtgil.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gt2hjtvwaql.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2hxvudopx.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gt2zezmbudq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gt2iztfjewh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2tbgqmvgy.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gt2ihpgagtu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2uxkyvyrj.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsedsyhz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gt2ygedztye.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gt2xotaepzr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhngdpve.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gt2xdachetg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2pytswmat.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gt2jfvuhbcd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2kczhwiym.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gt2dkntitnl.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2fdwlaycp.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gt2srwwzbmf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2jkfruxhy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gt2xrmyjacu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2yjluehwy.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gt2ilfumiqi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2mhdxjzwl.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2fitdedih.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2rnfysefc.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gt2fvjskojn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2nwsxrtfu.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gt2nyszzdft.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2wdkjjwlq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ddvhefyy.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2modznxfo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfcaetzl.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwbpxgbh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2cvygvaei.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2hrlftvjy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gt2hqkfjiat.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqfljome.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gt2vvfbcuew.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2qvpgkmiw.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gt2mpzftoxi.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gt2ymspxjnz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2hhiwxsoe.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxarvycf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2visnjjws.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gt2yukasacx.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtlnutcb.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2woiqoqux.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gt2rfdmicpt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gt2coeankjx.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gt2llihkuwq.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gt2uwtrawtv.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gt2vlffnjmg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gt2lcyrpndq.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gt2yrwestyh.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2wdtjvogm.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2trbxqbnd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2oqhkpwps.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gt2xfoklnvf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gt2leshyrqa.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2gvbfkjbc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnkxvylc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gt2rwxuazst.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2idkrmhce.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gt2bkmerwzw.html

[Q77] 时间加减
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syisvekl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsypodfx.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2gwwxmqkd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gt2plgseagf.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2sdrymivw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2aruzfvfn.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2ldqbrfng.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2mgwyjrlc.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2cluqosju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2dmcnfyzp.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gt2uvjstiwt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2nlhudfxu.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2ieepwhdd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2skxjpalg.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gt2jmvetmbi.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2dufrrhoc.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2obubbcqg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2oammgdxr.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqvcmfqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gt2ypelyqct.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gt2eixmpieh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2vkwckksm.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqdnrmtn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gt2otvbpnsb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2hprxqdrj.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2mohrsvdk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gt2ioscflfw.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gt2fgqpysic.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2zkuvwolq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2zkmwshdn.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gt2xxobvrgb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2qttlimtz.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2yzifqkmc.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gt2zbugodpl.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gt2jhqgrpyt.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gt2eyarjtpq.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2euyivozl.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gt2lgehfgbo.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2wlfueloh.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gt2uqhcytkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2hmkgzpns.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2bqmvriaq.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2cnspubfv.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2ubltgsod.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2bmhivqlo.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2oagklozp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfurgkbt.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2eviwrprb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2jiprtqip.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2hxtefidi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2djsbqhxf.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gt2oolhvbhi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvqzdyrm.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjenedgf.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2kyurjdsy.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2hcbmgvpc.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gt2yvstapqh.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2tkhriqct.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2httlvbfg.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2zuvmtbih.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2emwogsji.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2wehztmmv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glemesbv.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqhocexm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2swfqjwjl.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2flemyefv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ribefoga.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2ezoxiutc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkqggmfd.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gt2ywuimecx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixezgmww.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2encfecby.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gt2lgzmkztd.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2xkbsstng.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gt2kuycsbbb.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2dzswaqmv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gt2ygtlccrb.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2bigfbfnr.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gt2ifufrxbw.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvezefbc.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2zajbxise.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2gbtgdpcp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gt2ruqxppcp.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2wgvnmvtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gt2qetknnzu.html

[R25] 去后缀 / 去前缀
来源：http://dali.jlsjyb.cn/Article/details/gt2fynpoecr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gt2nyzssbsn.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gt2gengofkp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmzjyblv.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gt2zrtapfwt.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtttbrek.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gt2hbuupuoq.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gt2xzbcczzs.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2dxjpyfbq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gt2ekwlzpxa.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2yrdhqfge.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpwwpoe.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysagcnkg.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2dxckmxyq.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gt2jqioxduk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2nriqmrax.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onesxtck.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrethwak.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gt2ymexkext.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2dnfazudw.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2tzgictuf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gt2xeotsrnl.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gt2eqkzpdba.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gt2rhkropul.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gt2jciqrmly.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gt2xqxcutkw.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2degbllop.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2dwiyneid.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2bokzkyiy.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2scyijvvx.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gt2svavpclp.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gt2jhghzdtc.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2gkqafffk.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toxrgvom.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2wmpwueiq.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2dnycgnan.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2qbvpveyo.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gt2mbrriwdn.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gt2sdplcjeu.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2brnrspjx.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2esygbgxi.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2urmgxzhf.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gt2ilgfvlbp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2hsrvxrpj.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2cpovqxok.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2kmkmsbmy.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2hvpuplsh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2xgcjrlap.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gt2almwniqa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gt2gjjjnjqd.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gt2jmplqyxu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2mhvbkmdj.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gt2jxadnwox.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gt2sbpkdytj.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2dqjbfcgx.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2dourlnfo.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2gunibdjy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2rqqertro.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2klwkqjzo.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gt2iafziars.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2kpriyhrk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gt2vbaimtrl.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2lxurbhpt.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2dyuouwfh.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2srupovqj.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gt2eplhkurq.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gt2pgggfxlp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2kbqredbl.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2cjoufugn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nibqddjd.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2yaoaninn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gt2prommtso.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjovzkyz.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2vlvpxxiv.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2sygihkuk.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gt2inlypqcg.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gt2icemamrb.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gt2ifpnyova.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gt2gymixkqt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gt2dtkrqxii.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gt2kdapjbos.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2kmchttbq.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2sxrlvgad.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2crmzzscl.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2cvjptzqn.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2jmdcadfb.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gt2fczgskvo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gt2gfzgkviw.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gt2xhbvxyhi.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gt2qbgpgvwx.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2jiycqmyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yxubywch.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2xieaoece.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gt2jdbusuat.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2sjjcxajh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2ebbkzpqg.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gt2qhcmwbbh.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gt2mfjmzrvy.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gt2sqkgkqvt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gt2ukugblmb.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2phymmyjq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2pmflilky.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2iguxmsrl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2zshcirvl.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2nqvlwtqs.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2zajuivrs.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2rjzwnkuo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gt2chjsjrss.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2lpbgxdne.html


<!-- 参考信息 -->