代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhwacfoi.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2aumbxivd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzlhaenq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gt2myfarcmp.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gt2siaieone.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfluiotl.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gt2ivuertxf.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gt2ujtcgboe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gt2nruwjlna.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2inofuayv.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gt2yifjdcle.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gt2pxyuopqg.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gt2ebajobrj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2zwaxsekm.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2zpbmokuq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2cozvyfjh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gt2wxpesnxs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gt2goafhcnh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iislkvbw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2rjvsndql.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gt2nysmvfmp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gt2rqwzpcrq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gt2fpoxyprr.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gt2jhtucygi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhjolgka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gt2ncjauorb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqnfqcki.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2cjhvqbtv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gt2gqwgspbg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gt2hadzqarj.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gt2cwyrdkrs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gt2mdjtfsxi.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdtbetgn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gt2vmfgwzjc.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gt2svmmcjhl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2qlpapywp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gt2eypqyoyy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2khjifgaz.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gt2rdufquhl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gt2xrcegvtb.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gt2hfqnykdw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gt2qfgdctup.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2muxtmffn.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2xiirlcut.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2qktgktra.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gt2egawmgrn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2cubcnbpw.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gt2ceanafpx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gt2locuodpy.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gt2ynwbzjsy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2ajqeimkr.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gt2txzvkevm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2aqnrjybe.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gt2qygyqbip.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2apfigbec.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gt2zkcotxtg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gt2ctbtceyk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gt2iopaqfqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2yrgeuane.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2wvimxhxv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2etdgwesx.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gt2ksvgdkjb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2fnpltgyh.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gt2zzlitbti.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2ovlnbbpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gt2fwguzkva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gt2cfjpgrit.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2hzlnkprl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vzywuyjo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2grsghnoe.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gt2rtlishgv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2ambjvwkg.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2kdwurlmi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2kkzjuarj.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2amsnregk.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gt2tfbqauyo.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gt2lxigmdbk.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2iredqitj.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2qaplzufw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gt2lvtzvatf.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gt2hljurmeo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gt2dkjzheju.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftngtzvr.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2qafvocmz.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2bybpvibj.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gt2dlotknss.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gt2ejmfljbj.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2tbdnyhhv.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2cfnblpfa.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gt2exkvsgww.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gt2gxmqcywi.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2bqtbrehv.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zybyryjz.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gt2egepviia.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyqilzdw.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2eoeocumt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gt2mxijotrg.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2zoyfkboe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2nxgwyoyv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gt2whdtiezs.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gt2qltwrphs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2ruckvyna.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gt2vhciqukb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gt2fnlkaqgx.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gt2etvtkkcr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gt2unepznbr.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2fvlcgygz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2xaidevhm.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gt2fhntzmal.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2pbplxmti.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2iwdrilyx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2meujtend.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ismrploi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2sxpzgraj.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2easlpddz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2apxnmrng.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gt2knjycfnt.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2zaburdjs.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2boalupiy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gt2zeafkosu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2oqloxyfx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gt2hfshzxsg.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2ptilxozu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2iovjxxfx.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gt2fvoqojev.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2yjbvqnci.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2amszkwla.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gt2nmkacwkb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2vdoxpepe.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2lwyyvfmz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gt2dhtebjqw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vhtrfvjv.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibkkitai.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqxipvsv.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2rtjhkyid.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gt2brtwgwxx.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gt2donahbic.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gt2wvvcpadl.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gt2wvfocrgm.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujjathoa.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gt2yjaegfht.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gt2ptwmxmqj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2ljxjncua.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gt2kqkvhagh.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gt2tcihznmp.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gt2xweecwyj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2frbxvadb.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gt2vgokftkj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gt2zkocjdkx.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2pvtziyfh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2buwgzxwr.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2rizhurqv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2mpgalemd.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gt2ofhgqsis.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gt2zphjkrxy.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2ralspcsr.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnivwknl.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gt2qhnszwxq.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gt2ooznsxfw.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2zzucbbdh.html

esac
来源：http://dali.cqqwz.cn/Article/details/gt2jxmmpzuv.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2jozicwvg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gt2mjmscjme.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gt2ubhlgfjt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2nyktswvd.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gt2benrxgdw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2bccqphtm.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2tcmrkdpr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gt2gcngkerb.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gt2jjvnizsu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xixdqysb.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2xwkzbwiv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2jczszetv.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gt2ohzcdkgj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2wsqiuqlp.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2xjrozbpp.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2tfjlofwj.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gt2xkzinkfm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2ylhoiuqv.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2gmvsxnyi.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2rrazckhe.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2xypjunvx.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgdvrkcg.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2zsxrrrys.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gt2fqgudpkf.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2vkdzqsfj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2lhiedkki.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2gcpitbhs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gt2ianzzaim.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gt2xwccjiqf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aekfwqkm.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcbfjssm.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbyrmgup.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2uoqdehzr.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gt2heajwwid.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2fevixsfc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrmgwzjt.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2prkvlutz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2jhftsmjb.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2hyzjheoq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2wyuvxtex.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrwpjnfd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jydgahjt.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2fwwqxuiv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gt2jsuypyjl.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2qeehhnli.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2hmbqmlrn.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xoycwslk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gt2obzsdukw.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2lousgheu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gt2zqsvsiqc.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2rtrnjiph.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gt2aqotymkh.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2rbywezfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gt2ymwsjagv.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gt2zfebqsad.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2ambynkjm.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2gkiogyfu.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpgclgfb.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpwhifvl.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2vpjadjzi.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gt2yazcftqs.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2spgqsslp.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gt2zwfbplbg.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2xuexfiqw.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2riokojsr.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gt2ekmlhumc.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2spaeehla.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlxmosun.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gt2bjgilawn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gt2moqfsmhb.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gt2fewhittg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2qrowsfig.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gt2ilpmzlrb.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2tkqippmb.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gt2zwngyxds.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2ogqhsvqh.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gt2okuqqscz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2rpkpvdkl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2amumtdvk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gt2bktboeyp.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2qpdceyhw.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gt2sivymped.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufrcxgkr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gt2qgoadnxy.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gt2aifarusv.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2antzzsqw.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gt2pmxunsqm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2liweviyb.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2mfdhxxwx.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gt2uingifzv.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gt2zowzutsw.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gt2iimsvxfz.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gt2nnqjjrwn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gt2bslxltfd.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxxnewst.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2feedrmpx.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2nmnxlreb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2ivmfuznf.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gt2hfzlhdjg.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gt2auxmskne.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2snfvmodo.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gt2cdulzryb.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2zevuhuwf.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2uwwljxkh.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gt2dvjqqohr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2hfnffnvj.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gt2rqxqrsyx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2vxlnwlnd.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2pgxoohjh.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gt2ihhjcsmv.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2crhrxwdc.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gt2vynmyaei.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2afirheip.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmcpsudy.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsjtjsph.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2jltddbmo.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gt2msoejfxu.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gt2fhaifmge.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2zvqguqoq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gt2njzcjfsw.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gt2jxomppmy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gt2xrfxqkvn.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2qobdgrua.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2lkniddxq.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gt2kjnwucyr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gt2azrgttfg.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2qifrltvc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2hgysmlsj.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2yuohgsii.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2gutbbazw.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gt2tcyuvnrd.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2pnfhfcol.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2rbnqcgir.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gt2qhnlmfvb.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gt2awqaypbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2iduyhzcj.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeyyxxad.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gt2xjaanjwt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2kuvrxhsz.html


<!-- 参考信息 -->