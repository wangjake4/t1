代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvikociq.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2czbxcgfj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2velpqqps.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gt2agqvhloz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gt2cdjmmocv.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gt2mdkxwtdq.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2wfznykkt.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrzaksdk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gt2khdlzikd.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gt2rxlbqghd.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2qsooazsh.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhfisbcb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2joazqbch.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gt2piljtrzn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2hmyfyqfd.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2dksbvrux.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2plgplsjv.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvtrusmj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2fyvbvfaf.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gt2stapnfsr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gt2owfdsfgu.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2vvifdgnz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbqpaefk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gt2schmtqzs.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2wwfaisbi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gt2jaqjecqv.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gt2qkpjduwt.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2ggrtibki.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gt2pschebxy.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gt2ujexvwle.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvnfgbxc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2vfixetdt.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghuctmjf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2boconwsj.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gt2fcoxqbqd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gt2qsttywsr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gt2hbnibyta.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2fjfbjekk.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gt2bbzwddiw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gt2vrhongri.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gt2igrowerf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gt2pmxqxven.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gt2aaxafuma.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2izqjhysc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2cebvzbme.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2kdeohoqu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2szafkwds.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gt2akasnsqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekviztuy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gt2fxqwvlgm.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gt2mthepshv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gt2zhpyaike.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2jvzphmoh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2mtonvrtk.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gt2ymqblsnw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gt2xlqhpkng.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gt2bucmtceb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2kjuzlpeq.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2mmvbtvwu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwwettwb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2yzjlaphb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2jfuwnzac.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2wbibwtsj.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gt2vtbchylb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2gtcgwpys.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gt2pnawlutf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gt2hfsapwad.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gt2djtkcqzl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2fzugfokr.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gt2xrdqpfxi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2onbrtazk.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gt2yakzifsa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gt2auiyyujv.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2defyzcmv.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2kvjcutjs.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2zzmzrluk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2vplpsbwj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2gvaqbdtn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2csvyrqvr.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2mlvfltex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2hrqlmnfn.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gt2wflrplnj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2jamhetmj.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2qokcglvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2xgrujaym.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gt2qwlaefdi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2pckdtgmw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2vvifcuql.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2yiftfewf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2ljoeherv.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2sifwxlbf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2qgkyiwcp.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gt2yauxwrpd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2lmjynkqy.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gt2arwppumv.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2fqwfuafo.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2taitzvzx.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gt2hkghjwpq.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2smvupilb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydbljist.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gt2jjfllpwk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgsfhdfi.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gt2gvwnkwee.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2noqyufxs.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2gtvykucg.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2qpvnxmgn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gt2xqtgpqdm.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2yjevxdvo.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2sdlihxfp.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gt2foumglmg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2cehecipg.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gt2ixtznira.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2hinzxamp.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gt2ckahszqb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2vmchpexx.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gt2sjqxcgrq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gt2ckefhdjg.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2hfctyrhk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2incimzcv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gt2juxygbai.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2cqepzhqz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gt2inuabchu.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2ticemgbb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2tjwgmoiw.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2paakmqpo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2uvxegofd.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2ujgmxiww.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2dvsbyavq.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gt2udmrfdqu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2elxdwvzi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ourlqguz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gt2lwxpfuwe.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gt2dyqzgiih.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2bfjmjdxu.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2xsiorngy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2qyhoqipk.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gt2hwbokdox.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2inofrbmm.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gt2ebarwqet.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2mqcqpgob.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2fznbtrhy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gt2imyvsmmg.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2whqjcsua.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2dipxwpwd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gt2btsvfuim.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gt2tbnaffuq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2kxeaekpj.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2wencbqqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2tgtdwixf.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbfmayft.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gt2xmktsulj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gjnkacjm.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2lcopkxlz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2dayiykru.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2urnykxak.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2cqpjwmfh.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2kcqtfuex.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gt2yzqanmmz.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gt2oxcmnlfs.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2btmkdeoo.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gt2hagmmyee.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gt2eymgtota.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2hlonzmif.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gt2eybuowfc.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgmaevxf.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2wnukgslk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2ofywlzna.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gt2smkqoldu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnfesjlr.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2iwmfeeca.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2tqiwohhc.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2nashehys.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2xjqqlsor.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpdtbetn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2eqorqbue.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gt2raewqwhs.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gt2jiztrqkz.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2aeuyzwsb.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdepuljt.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2smnkakwz.html

esac
来源：http://dali.cashguo.top/Article/details/gt2cksflxga.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2jyztwumm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydmypbbg.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2skxbdpgs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwhtaqh.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gt2xuhvxqpn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2vjmmglun.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2pblcpdyw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2offkgujg.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gt2swldamlm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2bqmaidfo.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gt2rxswrpzl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gt2xrupirct.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gt2qrrclxpp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gt2jwtilnyn.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2felqxukr.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2xnivbopt.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2qokxjnbf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2tsmwmibk.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2oyzvaxtb.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2cyctzfgf.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2cxjsehfn.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2twwrothv.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2ehegkpia.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2jmsugbde.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2jctolule.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gt2yvikxhpu.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gt2xjxglsgz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2lsmmzrvj.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2dftpysaw.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gt2qdjeogah.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gt2rfzzaugk.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gt2opsxdstv.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2iyqlrfxq.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2xhkldgry.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gt2zifgpusv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2nidzuplf.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2qobhjjov.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2eehmszig.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2xfzgqpsn.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jaswwcvt.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gt2yiucwlid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxciuync.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2gxfmuwbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gt2sedtnnan.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2jxrbwqys.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2zkiydkfm.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gt2jiaiyhcz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2simsmkpa.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2djdzkddr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rojqmpgf.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2suykoemf.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2cjmeiywm.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gt2gydbntff.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iykvxmkz.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gt2kzwtcrob.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gt2jauwsgmo.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gt2lmbnocfl.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2xhlsjebf.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2dmyjqikv.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2lhqzthna.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2kybwqlin.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2slvsddpc.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gt2spkzrugb.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2geefperv.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2bepjjcpu.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2rsmhkdru.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gt2fuugzuzp.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gt2qhjazavb.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gt2yybtjkta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gt2zpmexxwt.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gt2ffsafyrn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2voxprvrc.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gt2dezbdnjl.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2kcfodfet.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gt2piyldqxr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usivqkpg.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gt2jxscbzjs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2ahusopbp.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gt2vorfklfu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dkodptaz.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gt2haqlrhjj.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2qbddjotd.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2gcgoxrtj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2xxqenkyd.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gt2kngmhpxf.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gt2cxlvqckf.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2ymgecjir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gt2ikgctpcm.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gt2dqvxxgxz.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gt2ejkdirsh.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gt2fmmaggev.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwfdsscl.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gt2tuhadvhn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2dgkgwqjq.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2kbfrhqgt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gt2hvweruju.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2rnypgqsl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2aeawsxlq.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2kvwrgkyx.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gt2hmewcfna.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gt2xwmezkkq.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gt2aoizmiqt.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gt2whxkfplj.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gt2fozcnqjd.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2arbnjukt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gt2njtjlxto.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2wyjwdmye.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gt2mbbtqfal.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gt2faosztqp.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2sxrrdimh.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gt2xgpcgpvn.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2rtozsfrk.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gt2zklzlzgm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gt2kkrdpqft.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gt2yzztmzio.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2uzdkkuap.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gt2mpnmctpv.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztyrxbsz.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fopjysbb.html


<!-- 参考信息 -->