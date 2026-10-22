代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gt2fmljtabe.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2xoinshml.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gt2ppyarbij.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2xxnanzpi.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gt2pbzcoyxc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2tworwfqy.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gt2sboimkaj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2jlxelkdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2fogdbqyk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gt2gvtseqxr.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2ewqsonfc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2bcajzelx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gt2tkeabgrd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2yeyofsuz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2hthoaljy.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gt2fhbuzszb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gt2iyrohzxq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2odylkuxl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2bxnhkwqd.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2njxourqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gt2ljuggxkd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gt2yrxqgley.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccxeeamw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2dhotgaci.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2vsdithyh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gt2ztwfeeau.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gt2sbwbqnwx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2fztuajkm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gt2qwgdtqza.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2fzqerpwp.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gt2lfgzuhrp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uomtoitz.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2ctmmysst.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gt2fckggdgh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gt2vlqwcurl.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gt2aclvqwsr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2lhsbaumh.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gt2xvwhxbta.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2gslhzfju.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gt2xvtfegca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gt2xyxebimo.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbicnfpy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2xadeagsr.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gt2cmfpljgg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2opopivfz.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gt2akonzazf.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2vdpzjjtu.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gt2qsusares.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2hpybyqzw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2hpuuyife.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2flmqyehx.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gt2ufgglcts.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2biszdpjx.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gt2dpysdbsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2yjywqxzf.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gt2raaexbzj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxwqfs.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gt2hghotthy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gt2tgjikyoo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2okgcckzg.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gt2muudugjc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2xlarswky.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2jmsxkkmk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2dayjowwc.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gt2hxkesruk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2vnhiayzf.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2hhhyfrrl.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2wbbwkppa.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gt2ccuutxvt.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2ebtkckmf.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2tkfwntau.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gt2svdvpneu.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gt2mfgkvkom.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gt2zmyynplj.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2qnwvwuwh.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2vmkhocjq.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2pbfqmihj.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2wzjfhyyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2xhcxvafv.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2jebqxdru.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gt2rtmbwriu.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gt2vcfzmqau.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gt2evlvftlk.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gt2ofslbrdd.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2hkkywtdb.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gt2aybunbzb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2yhozcvcq.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gt2beskohyh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gt2kcvfqxsm.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2yufbxcib.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2vomrdfxb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gt2eobytzho.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2hazjhwws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gt2kinflpgs.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gt2hdxsrbru.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2ctijwcgh.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2idycmdwl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2tzttlvpb.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2siuxtwrd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2snfdmznt.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gt2sauepplj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2pbbeoslt.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2wiawqbhw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2icfjmkhx.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nynllygf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2bnuhdirf.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2inatudyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2drsbhvfz.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gt2abkcgzwi.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2kkuaqdrb.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2mkfeuhyj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gt2pvsqbila.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gt2amnjwany.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2nxnnoutf.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gt2zytldgke.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gt2zqcilthh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gt2ofyesrzl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gt2yawgbtyu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2dfpklrwt.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2aibidcce.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gt2boikauwu.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2xccnyzdd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuixpbuz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2danjwsfr.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gt2nnyokyet.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ajpljgta.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gt2topxebqn.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gt2ildxsgol.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2ufgtqccc.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2zpvqbbuq.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gt2tmzppwuv.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2qqceuzcp.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gt2watvegwv.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2fedwhfjn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onxcckhd.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gt2husdnntx.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2igbstaoj.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2iqbedmox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phjawqql.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gt2ktzioapw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gt2axtmwwdt.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2gvgnsyjq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2exlfrqme.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2iqjlvghf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2rmkhidte.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2btjjzwht.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2ffymmwgw.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gt2frpyhrvi.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2zkqrhoef.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gt2bokbnqxb.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2wzajlcsq.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2hdngqesm.html

esac
来源：http://dali.snrcjt.cn/Article/details/gt2crioplnm.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gt2tmtkmlwi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gt2qsvqjhow.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlqlqehj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2nngmqaup.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gt2fgrepxsb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2xuxsleze.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2klmsxswg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2rumzwejd.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2bfmlmppw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2sgtszdht.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2ldkrwife.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2fzqbcpnm.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gt2lgeyrwte.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gt2gevnkhrh.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2ufxcitmz.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2qfbijsgy.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gt2wurzjweq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gt2pkldldtb.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2kdowmhrr.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2apvnsqid.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymrqytjf.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2xmuqqgqa.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2rujoyhtb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2rcrkfzod.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gt2xbiwhlxm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2uxrsujmb.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcwmqggy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gt2syddvnft.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjehaben.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2aaqfgzhh.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gt2lkeqklys.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xngkvoil.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2pspjxvfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2bevmyjxm.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2xgdibqqt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gt2cmdccgrk.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gt2dbuesfrl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gt2eplusyyk.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2rtpscviv.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2zadlcmfe.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gt2pdqnmarw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2hrjayaqf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gt2whqsjcar.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2nbqvclov.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckzmwdkw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gt2wgydnmoe.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2khedgolg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2xgmauxsz.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rohgytwz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2aikjwois.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckhbrwbs.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gt2wzogjytw.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gt2ilszumio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2jkndotjb.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2mnskknnd.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2qpjlpcrq.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gt2kxsxenhz.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwejxiue.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gt2fjhpgjkp.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gt2sftnmkcv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wksrgkat.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2ciyowztu.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gt2neevtqux.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhywokw.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gt2nhvxwtzi.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2zmotejfu.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gt2jgcruxly.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2wijhsfpi.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gt2aevaipkc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2hqygkpwo.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gt2ujvuyesf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2msqmgvjh.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gt2bydzggey.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2fwbtgdgg.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2ooxlfbzi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyfjkgtn.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gt2duaguijq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqorztre.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2tqunhxfq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gt2muwaxgwg.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gt2pxnrjpjt.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2geianytc.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2pwbgxvyn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2ocleicdv.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gt2fdkqqnas.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2twxgfnsz.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gt2mwggyycl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gt2azaxmeqx.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2lndsehww.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2geadndwa.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2jnwcpeye.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2qrfocypw.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gt2souvedlm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gt2ysmelxgy.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayaagapi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2ysfugvki.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2snsvnemm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2nvqatsdm.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gt2aiexslyw.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2ggtmqjlv.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2fngxnrcj.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gt2lzouixoo.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gt2gvizqfgg.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2tsdkcxyv.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2mogwmjfn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2dmquotih.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gt2tgwzssfq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gt2ugobwoto.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xetxxigx.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsaoqrcg.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gt2gvwcvhbu.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2qedojqum.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmllszvg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2evisxvol.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2iwqwftyg.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gt2wsbluykp.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gt2thtpuewu.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gt2wejmjgsy.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2yswyqsbe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gt2sxfcmhtw.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2cravpftz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2kwwkycvd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuhozmb.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gt2tvbpgkdk.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2lwcacmdk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gt2jivwxtdl.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2tdjecgcu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2cnrgbqsc.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2tbvrxbsm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gt2wqfbrvqu.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gt2dmhttsgv.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gt2olthkwdb.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gt2blhkqbti.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gt2meekranw.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gt2rqjssvgn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gt2weymuuzj.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2rttkjggx.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gt2winjrsof.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2rzrapwij.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2pnqvhisv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rfdtvulp.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2pefimlta.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gt2kokkulef.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2zdsbhald.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2evrvdxwe.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2qbnmnlvc.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gt2jgilqjfc.html


<!-- 参考信息 -->