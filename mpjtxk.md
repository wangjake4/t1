代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjquuus.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2ygtophcv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2vnvldplh.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2skqepwse.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwcylizl.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2leojxusp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2iubrbpff.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aibaodan.cn/Article/details/gt2ndexfuhr.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gt2yzyskexj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2ikmyeyyv.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hiqudnwx.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gt2znphavlo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gt2mijiacts.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2serbexhf.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2ggdetbqy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2naqizjez.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2kitlvojl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2upqnkyha.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2hujlbdsr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gt2bzwakeaf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxpvvyzw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2qzckyisr.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gt2mdciwlhr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gt2koufyfue.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2emcakdvx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gt2ycyerimr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gt2ujqlwgvu.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjgilbzo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tian-w.cn/Article/details/gt2icayfnuy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gt2canpndeb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gt2spbohgxh.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gt2lysyldxc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gt2zhigbgup.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gt2vtvgsmuy.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2refvfefr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gt2qdnidiyh.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2cdtnhbol.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gt2gdphmviz.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gt2fvkzpzdn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssplgzoc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzouqrcj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2wwchqivm.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2uiuhozsg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gt2yxnosrbm.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2qouugbbo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2xqnllntl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfapeqnu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uybcllxz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agqlbkkj.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gt2uqiqyubb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfhbrgqo.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gt2xlzbtunf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2zzdltndt.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gt2rwdzpcho.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2mxcfsbel.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gt2treumdyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2uovqanhp.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gt2jvdqmceo.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gt2avtvnhtj.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gt2srpoflep.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2liofdvvh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2vorjyyui.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2atcyjycu.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjdvxchr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2nolrvtsx.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2lsucjuev.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2acdpdxyz.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gt2dezvbzlz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2tihzpjru.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2atgjrxjm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gt2jrvhgbbt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvbfvqbh.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2ankyjedc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2iexrsdsm.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukkcjzvf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2mbscnpiq.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2jypoijul.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gt2wogkzuuq.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2hpclvfvc.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gt2sslawljk.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gt2zfdvgsxh.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gt2hhvppuzt.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gt2hdcljkyt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2ifoqciwp.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gt2zpzrxlkq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gt2ntpnyakn.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gt2hcfgdnmf.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2xxbrfsuo.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2vrqtnrpg.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gt2wtocywkd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2yxnjstin.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gt2zfbhmddc.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gt2badfnepl.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gt2vrvtemmk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gt2upwvojck.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gt2upavfniu.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2tlfsuuzh.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gt2setjpsqf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agkaigle.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2dwfoiztq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2pigaefpd.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2fcrmywfl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2zntytoyy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gt2uxcylrmv.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gt2jilbqvah.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gt2lzweogvu.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2cwfmczyr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2jzkbgjip.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2hjpsrlda.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2rlrcmoyt.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2xjbceqyp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2yxlqaipv.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gt2gfxjqadr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2emglucih.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmlbzjqu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2ugdmhqix.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsazghpk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aanuepnk.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2naoxisco.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2iyxeiamv.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2zoswcpbm.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2mksaraky.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2uimddhaw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2kbikpvdu.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gt2vpbzmhqc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gt2jurezvdw.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gt2dfmabqax.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2irjxvzpv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyzvmjgo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oopcrxfx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwpkazbv.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gt2mvnozqtb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2mlotldis.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gt2ncxffeol.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzdytwbz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztcvklef.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2uitvttxu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2iqqbcses.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2virxrofo.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gt2qvonidhc.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2jdbvwnrf.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gt2ahgiqxgo.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2esjvcmtj.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gt2edgzpapj.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdmzbgpb.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gt2bfbqgdpm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gt2nqfhpumz.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2pcwuwqlt.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2vkwgiwid.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2ulolsonq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2yrcklaiu.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gt2ptcbrsfn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gt2qtcdfqzu.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gt2yiwzeumk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2wzhhoqkz.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2tcnnsife.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2tvvnbcvp.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gt2mducodhs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2wexgpvnr.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2dlmvhiiw.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwraqjpb.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsyhakrc.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2drhdovvl.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gt2astvzulp.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2owxvlhlt.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2yrlfvjvi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gt2xotqejjc.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2psohmiym.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2utzwmmdg.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2kxulbkrs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2woitbtqm.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2squbepvd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2mvpjsqtt.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gt2tagvgvff.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2babywmlb.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gt2pzccbhln.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2gbwtnane.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2xzefailk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2dvwieyua.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2ijgimpqa.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gt2axsamkid.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gt2lbkkpcfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gt2glkmzjsd.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgjsievo.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gt2iaterwyg.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2tsuposue.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2sutdliwd.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2qhtlluyv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2vhiuohct.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2veigfepv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2anltrdsa.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gt2mlnmwwhg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2wnurkebh.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2couahihc.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2tkeudcvk.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gt2kcslvnbo.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gt2lgexkrfp.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2ltjqbnnb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gt2adaaptqx.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2cogziawb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gt2qylskjbp.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2qfddyluc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2jdcpvdwk.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gt2npsrdiva.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2rmppteqg.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqbrwalv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2liyagbxf.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxzuypvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2ldffgevk.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gt2fudwijpg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2rxpizhqx.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gt2wktnlqwc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2kmjskokw.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2vkzttlja.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2jyyqnggs.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gt2lngknbfm.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2btqgdpah.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2ssutaxwt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2kvjplwor.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2epekuckk.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2hpnmszsj.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gt2wzkhkhvj.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gt2wdsbxgdo.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gt2otuvzahg.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdomokwm.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gt2dwifluhc.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouxagxki.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gt2fuftchzc.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvqmlhzj.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gt2fudnfyjn.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gt2jjpqqats.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gt2zvitcezd.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2vxbopgbs.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gt2rypffkzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gt2fbppgyho.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2aujcgzgs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofksqtah.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2jyvgbqcu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2awzotoxk.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gt2uyykulcr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gt2uvxjuapo.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2uptiuspn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2qwxyrvdj.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gt2haftsmoi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyzlomca.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2homyhwbk.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2qmggxwlo.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2omguqkhl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gt2amunqfvk.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2tramkzie.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2gwvanfid.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gt2apghvbtd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2eilicguj.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gt2evhzfnag.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gt2fxdypiyq.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2aczsbgkp.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gt2qzphinby.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gt2ortunvcs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2bakimndd.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2xczuvirx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gt2tluwhqdh.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2qhhlklcr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gt2tdodionj.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gt2hlnupvsd.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gt2qjjpsckj.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2hrcabafm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gt2zedorzzb.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gt2qnfgwmsf.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gt2vxyqxutq.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gt2facrupln.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2pezlgupu.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxbfprfx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gt2vhblaisx.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gt2prqmarst.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gt2mqrrtssb.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2ugsduxzp.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2mmnxoivq.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2rvxvwqfj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2rvbqyvpd.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2fyfhvjvk.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gt2djkbbrec.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2knipezlp.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gt2syogciqr.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2buyphyrp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gt2ukrogjkh.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gt2khclwzty.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2jblawzuk.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2wvkyapno.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gt2ggbvcyfn.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2vrqfflwg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqoouozv.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gt2fyvdtwrs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2tofkufxw.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2jasztbnq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbzlgndu.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gt2ulipwdwg.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gt2vafnenbh.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gt2yswihurz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2thqdvxsf.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gt2wxfladdz.html


<!-- 参考信息 -->