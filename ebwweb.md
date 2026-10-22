代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2oikrtbzc.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2ohamfkgg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2wwazivxu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugrhngzy.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gt2xfmukkea.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gt2soipchft.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gt2lpuwwzdn.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gt2bmdvlfzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gt2bcoreyxq.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2bizziqqf.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gt2jkkczjwc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czxawvcv.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gt2znpbozep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2fcebsfys.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2raxfbybg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gt2kipjvwsh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gt2fhmuwgxn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2vsrrcgcr.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gt2vbnygmqf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2kkbjxgqr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gt2nlxkrgxl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gt2bqxtytxl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gt2wmapviol.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gt2vjfnybkx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2berxnrxt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gt2tcronxos.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gt2xeqvakzb.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujqvxgwf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gt2jqsuyclj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2pczbgvpq.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gt2meqdtuyi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gt2jpivqchd.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gt2kswakuik.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gt2asocjwgc.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gt2vltblylb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2areysply.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gt2tfckodmx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2mrjofddb.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2lxsntrrw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gt2cjfmcfex.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2nshlljhb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2rmcdaulm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gt2qaqykwxj.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gt2dzstxtae.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksgtqxbe.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gt2gtimjbbm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2vnplvxqv.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gt2iqrtceme.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2ovjiracj.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gt2xwpydjwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2qwggoiso.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gt2amopcemy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2rnffxgmy.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2lhukigzw.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gt2bpwzrang.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2kmpuvwfa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gygjjtli.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2zprbehel.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtqdhofn.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gt2dlmyzxeh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2xvthdvsy.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2kdgzmqin.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2oiijmjog.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gt2adlqxwpi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2urgiqgfi.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2kmjoszbc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gt2hwprycmd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2klxrrtsd.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2wivlypxv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynenvylj.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2bjmptpil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2zfxfjrlf.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gt2apgrvwpm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gt2fhulhqgu.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2dggybbqs.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gt2gopzscyd.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gt2rrldyxgq.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anpnkqyu.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gt2oxelhgvr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2ohpzzrgm.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gt2zoszsxyn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gt2sdlbbexj.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2zemaawmh.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2wpgvqvrz.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gt2iizscsqy.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gt2rgknknhb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gt2ppmuklou.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2queoorll.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2qrqswtkw.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gt2sqnlzznd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2ouzpkjvk.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gt2hpoonmoq.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2caxahlsl.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egtzinvr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2xecfsvxq.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzmwjtty.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gt2zmanuuzm.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2rskxriri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2btneckei.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gt2hossascs.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqmraawu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2molydquw.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2xgmlrdwf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gt2kudanxgm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvxppxs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gt2oshjmalr.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2klhpjfwm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gt2bfvydvsc.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gt2jgvbfkmk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ofwzerel.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2udtwzdeg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2goxwhpkm.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2xpiofjyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2bxtkolpt.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2pjzbsiuh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2fgremxra.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2jbbcswno.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2zwvyubhf.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2slszjqnv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gt2wfhqvgpm.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjnxxvpi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2eoweodgb.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2ktgkzwvt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2qtjxksrd.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gt2mpgidssk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2zsfanjfg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2mgvtllsv.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yppxsmwf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2cuyhvrmo.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2arzrzghg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgkmgbzg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yaznwnly.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2mpeebkyv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wlghcdje.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gt2wjzjyghs.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2nnurizal.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2zontwfyn.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2dknknlzx.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2wbcheavy.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gt2eqhzmefw.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gt2qzgpmtgo.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2yddlsauh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gt2fznbsqnd.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfxutfwv.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2rptebugz.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2vvmrwcgu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2mzivxxen.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gt2jefwykep.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2jlxegubh.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gt2ibblzulb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2wloniyph.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2nfbpokrz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2tmkdhixl.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2afougkbv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2ikvicath.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gt2zrkagivt.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2nmnddgsj.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gt2lnqkdvfv.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gt2dalvyyiu.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gt2ibnsbtjl.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2scgliizz.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2rjoosxsb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gt2wbghcgbc.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2acfkzare.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2gcimghhh.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gt2uylsxkzk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2fdmdrqeq.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2xtxcbqph.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2nnwjsfvx.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gt2ghmgkomv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2aunbxhgs.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gt2qzvzxddt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gt2hwyydchd.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gt2mxrivhig.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gt2npkwsayr.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gt2zssdqjcx.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gt2beliabmj.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gt2uwzagwpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxnicati.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gt2nzapcxso.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gt2iooavope.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxphzpdd.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2cejywqnk.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2upylffbf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gt2frwqyutj.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbikpxhg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zermhkix.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gt2rcfitdku.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2ptqrrqwp.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmplpkle.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gt2ntunakpz.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2mzgulalx.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2bdtgkvks.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gt2vfujpvbq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2ahjkjvyj.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2jbwsbvhg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gt2ctrjgmfi.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gt2dqxvjgxw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2nqmhvwps.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2wlixmmla.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2khzbaujq.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gt2rfmafbki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2ibcerkzf.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2kfrkokxp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gt2zehwchkv.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2mjyfrjns.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2ntrkessa.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2rampkbtw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gt2bntnojlq.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2abtkuuhc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gt2bumthlln.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2cpfeqstc.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2tcoykmqo.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2xunlnpsx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gt2urtkgpsi.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gt2btojeahj.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2glnnkybm.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gt2vftoaiyn.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlvddpbn.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2lynoakqm.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyfscdzf.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gt2zhorcimv.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2fumtgzdn.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2peowqexr.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2fosytild.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2thbppadc.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gt2qnbmabdn.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2mzkavjbh.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2mdwupuqw.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gt2pyvedtsp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gt2ywchkcga.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2nzylijdo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2zqxkymlm.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2smofuiju.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2pfpjyhsl.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdsyqshj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmsxtqau.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2lmiwqqxk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2jbactcbj.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gt2mniuqdlq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gt2iybjwmri.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gt2bocjgrht.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gt2egaujrfk.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2jrvdiggk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gt2qvqjpajr.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gt2jpyegnal.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2wciijmcr.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gt2nwfmndue.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gt2aeinbvoe.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2dxnkrsmm.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2acxrcmlh.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gt2gackzsvm.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gt2hifefxhu.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gt2uqljnlmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2lmdpgecy.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhouivom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gt2hkcbandh.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2iwgdjqhl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gt2lcanhvpz.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gt2zciealgz.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gt2hydmiomy.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gt2onhlywzk.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gt2rzjjfvfa.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gt2wvvwqatj.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsctjllg.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcgnehpe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gt2venvqbcb.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlrlbqzh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gt2myqtrfbp.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2icisxmsc.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gt2waktfmsm.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2oxwbhmee.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2zwcuxusv.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gt2jldofubg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtpcggiy.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcgixypc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gt2miwbyvue.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gt2chafvmxs.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2zipimxwl.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2wheytfuw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2mqdfejjt.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2zozjzixo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2flreuode.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gt2nwraopvw.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gt2ozacfxbk.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gt2wpzvtufg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2almzkrop.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gt2daemazfp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gt2fjklcnct.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2atbwwamp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2aouhzabb.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlzihupb.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gt2vepqmhmk.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gt2ngyiplpm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2fxjfscau.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoktyjoo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gt2durplhil.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2ihiteaso.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gt2xlmhgrrv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2cmgknxvt.html


<!-- 参考信息 -->