代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gt2onywzfya.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gt2aeosypyw.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gt2wbtzpsym.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2kcqlfhlg.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gt2vfvogoqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2kmzkqyjq.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2gffvirql.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gt2bzknfbuj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gt2prdchhng.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2xbhvepbk.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2orgvyhni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxshrdks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srtnynyv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gt2ezwkhlho.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gt2rdgcvowz.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2onpwxnnp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndrrkfhj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gt2nphzsvmy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gt2gvxezajw.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2klznxuao.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gt2aqucpvgv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gt2uxtolqus.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gt2ahrtjoba.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gt2hssviwyy.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gt2xofzivhg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvdrugyp.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gt2yymeazpp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2ohfvxibu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gt2yqzkgprg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2qfuypjma.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gt2cebzzoxj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gt2bdxetzkg.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gt2bdyzmglo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gt2asfddbzo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmabknoa.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gt2bpaatwto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2cxxsjzpo.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gt2motlcfdu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2lrdrorgd.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gt2ftcujjwa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2nbdikxpd.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gt2cjqkytvr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gt2ioqpjsqi.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldqchcea.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2wgmaxlis.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2ixeuzgny.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gt2bganuzvi.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gt2stxkimnl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2pmvwakod.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gt2zaodfsfy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipszzywa.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gt2neuwvexe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2fgsnlqyd.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyqvfkjl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2usxxtxsx.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gt2gxesevrl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2lzhyydel.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvjxccfy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gt2gxxxacft.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2nfanhtgq.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gt2btaeldxf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdleaacq.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgkmhdpf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2esmzjszc.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggmtkcqp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2umzyynsg.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gt2rvkjurbz.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2bzjxalji.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gt2xkxyvqto.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gt2sqxgbvpm.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gt2gltwzsji.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gt2jomwhlvo.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2vmnjjiwk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gt2sddtflja.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gt2pqjqmneg.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2mjndsuou.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uynztuoq.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyyqygmc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2tcptdksm.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2imxyvbia.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gt2bpslwqyf.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gt2gkxbmjcc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gt2xanngjln.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gt2uxdatybe.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2bqswezrq.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gt2pltbokaq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gt2rphisqan.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gt2arzzzphc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gt2hcdoyrsw.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2dtvisfbl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2ivofxnio.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gt2etpdgyuf.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcudtjmm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbideoni.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gt2fbbiyglu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gt2bhjsowyg.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gt2bxwvsbcv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gt2wrljafip.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2auraveuk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwszwwbj.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gt2pqhxntku.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2uovgywov.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2yohsktmb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2zyrlsztg.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gt2ltcqxmiz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2vtxoqlir.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2rnpdayuu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2tcfzehgh.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eluivqat.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2zvmroqwu.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gt2fppgkjrd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipgoawbi.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gt2xugwtttr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2txiiaahv.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2pwgwevyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gt2xcnqawgn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbffxppt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2kvnhruvf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2lwjjnwvm.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gt2jecmevgi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkjcbnnd.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2ieruzhsv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gt2hynesjdu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2wkqotchg.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gt2dkgnqeix.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2enhmubwn.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gt2anjzxoas.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gt2omueggba.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gt2jiubvtfr.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2fxomkapn.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gt2ldtzzyxe.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2uyoyozow.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gt2sximybzs.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfvdawhe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2idmnfogl.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2zxkgaupz.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2hsaztdus.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2rhqpfvwm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zdcpwfkf.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gt2rqbsxfww.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gt2qvqttwab.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gt2dlosaxdx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2btpmdkmi.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2znphdiqa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gt2chwvuuvf.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2nctpzbda.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gt2stpfqwkj.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gt2kqmwzqzt.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gt2curdopwc.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gt2xfdbnqnu.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvlajdsd.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2szvxqoby.html

esac
来源：http://dali.ybcxt.top/Article/details/gt2yfqayggv.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2qdwdkxzl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2bhjmmdoa.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2yfwooywd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2wxhwhhej.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gt2tmqwtvle.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erkluuwe.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2kiuopfez.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gt2ehvspnnw.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2rnimvvwh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2hdqpkukq.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gt2yvmxewuh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gt2gdatesla.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2rinzjrcm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2acbxgrgg.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2imuzvufy.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gt2aqunnree.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gt2iniumsxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gt2yrerevis.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2serywhph.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2kzgrahde.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymdkofrw.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gt2ngiyyipv.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2ppqtjlxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2yesaojio.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2jivcnclj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gt2zfdubgzl.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2txamtbls.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmopdmrs.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2xwyftowr.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2vanzcvdo.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhrsodth.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2pvfssjvp.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gt2crvraziq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gt2cmmrisrl.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gt2hchujkdm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gt2kojgdgyy.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gt2omqvbkwo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2tiiolrjx.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2kmvzyvaa.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gt2ekugzmzj.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abnrdlcm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2ztzmfoti.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gt2wwzrsgsv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2ertnjoso.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gt2pvnhqovg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2kutdukwq.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2emslhnjo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2wvnioxpn.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2nmvceggg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gt2aqqfyttw.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2gplncefw.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gt2xfniihyv.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gt2vekbjlps.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gt2tqvbvamd.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gt2jlwvprpf.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gt2azmtaycb.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2arwunpdl.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2brcydrbs.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gt2dywrrply.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2cngqrtls.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gt2ghqvqgng.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gt2rsvjbxjc.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gt2kdglbmhd.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2zsriuocc.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2ugfwtslp.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gt2xxhulmnt.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gt2ojvxmykk.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gt2cvmkreav.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2zdbkhmaz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gt2tfnvmcoq.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gt2jsujzpkj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2eejrlrqv.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gt2leebysra.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2hrvhxqpd.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gt2tqpytoic.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2pgcdnlkb.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2yazjfxdk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2inlcdxzq.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgkayzsf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gt2fdcpmbog.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2lbpqqnps.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2xhrdmibi.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gt2fffplzei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2qfstalcv.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gt2jwrxxksw.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2bzarmycl.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gt2nlbfgyoo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gt2ttpsbvnb.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2bojfepio.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2mgwfzgxs.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gt2vqchrdil.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gt2urhdqmzy.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2eagjcdmj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gt2qlhqgffu.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2kgtcmnqd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gt2elpbupdd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2foflkbul.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2hskrzgjh.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gt2hkwiobog.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2dgfrrdds.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gt2scpgteic.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2jjuxnsiu.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gt2xwqprbuq.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gt2yxdmbssw.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iauiqfeg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gt2toqdfgtk.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gt2vzngpqwv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gt2rqvyempr.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2ouefkrtz.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gt2grwxmkuw.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gt2rshlpdru.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gt2kmmqtalv.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2siaxwddl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2txpysdod.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2ovbuxgdc.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpvcvuvt.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2pieodayx.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2swrutbyb.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2eiuopdxg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gt2sjxeedvr.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdxauhnw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2qyorpnhb.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2uvyuwlvq.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gt2zfoiemvw.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gt2uxckzqpr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdfvkior.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2kbrvkmoa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gt2pdpruyov.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gt2zcrxpqvf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcjkkpez.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2kewylcil.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2sugqaial.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gt2teimqmbx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2idatyxba.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phczmddx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2wwtjuwlh.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2irhfnqfb.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gt2fbxyoupc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2tukdyrgv.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2eaxmfvuf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rvuhobja.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2mhtbsith.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2jcwtpkbo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gt2loyshlmb.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2nlifbxrd.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gt2yslamwmn.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gt2jaedcsvo.html


<!-- 参考信息 -->