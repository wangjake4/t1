代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtouwxirrz.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtovugkrqh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtvfmfcnwx.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gtaspzgpff.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gthygmbibj.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtcbsxnutz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gttbhoyugs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtdbsswjuo.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyozhkju.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtiouvcvmn.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtlgtloheh.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtymmcettp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtkxcnsjnd.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gtrbmidxgz.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtztbkfqjt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwusfvxsn.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrcwcrjw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtufymhgdj.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtaojproxn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtuigrgwcm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtbbexsulc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtqqwolybm.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtpxrlafze.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtrvsfcjyo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtfxiylxmc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtpkzvndnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtjvatyqak.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtphniitkl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtgafzlczu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtmjuccccb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtdlwhzgcu.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtpapnkawb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtextmvyda.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtvgiunmfx.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtsusaqijq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtwvbcpuyn.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtgejqxocq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtwffuzrch.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtjjmutqiv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtuosalrmr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtgnrgwduy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtmvukvcyc.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtkcltmrrc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtmgmemfms.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtrbinwopk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtthxhirun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gtonzavnlq.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtvnniglgq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtojnrzxlw.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtrxffamhs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtuuofqprh.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtgfftrewm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtuhyxnyss.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gtmcewrtdu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtgjqfdhoa.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtfpyxiyzi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtcgyfdeas.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtsapdnrfl.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtgvcjjspz.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtwlavbxlh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtpmpjdggk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtjnmugzsr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtbovcorgw.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtrneqcpxh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkaayaxxq.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtrsitcygt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtxjznccba.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtlcoyylxw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtmcnuawdr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gthjgughmx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtgdfzqcrn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtqcyxedcv.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtfwqmmcsn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtveeihxuu.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtgggzsrbh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtsigqhggq.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtvneubgye.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtgehxjors.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtdcdfadhr.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtdqgwvsgb.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtweqkxblr.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtaerzcube.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtpslwcjfu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtxggtpcla.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gthbkppvlu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtgvkieocc.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtluosebas.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtdmbtqawo.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtcmzxkylg.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtiasyrqer.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtgffyvxqe.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gttzarizbv.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtihombtqx.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtnwbreddm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtnnakllds.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtzzsfoxxs.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtaenbmmkl.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtjbctallm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdpclqro.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtrjpcfwgg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtcdfcahne.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtrwdnmgnn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtzrrkrlis.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuowbpsvx.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gtjlyqqzdz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtgfmgzufw.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtupyewkqk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtmdykpxlr.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtuxfjstzk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhtomihz.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtsunfvluw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gtegohaifh.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtitgsevxv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqsehugdc.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtymbpepnt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwescgdl.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtdbxcvahm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtkgidewwt.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtjohwmpsh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfroxgtgk.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtwcvmdfla.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcadbsfd.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtdbjwqmir.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gtuifqhmxd.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtzlpooshq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtrouxcyee.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtjwnoxiow.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtwsnnahvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtkpxvwsck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtgeffpfhz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzrnmcnov.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdzkcoys.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gthvhsiluh.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtwtjexxio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtmswllgtn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqjcidaya.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtiwvbxgzo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjkxmomzv.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtnizitizv.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtxmoajazo.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtqfexwyzj.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtkestenea.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtlgrbulre.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtmneofdco.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtatpgyhmh.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtbxdwbjnx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtksuasdvz.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtvgtnorpd.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtppkbnhpo.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtjdgzdggy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtviwvmtdh.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtqbsljlbv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtmwtfzieg.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtxfjfgntk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gttbjvcpnc.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtikugmukk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtmeuifcij.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gtzaobsctj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtjavhqtqk.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtgdndlbmu.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtysxrugck.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrirdsmpr.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtdfwazfyt.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtgcjljtea.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtlcbckfib.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtiqixgcrh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtqpjqhekk.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtifxwkxvp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtqwwzgokv.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtcrkygonv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gthqbtcqrg.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtezsahhyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtgdeqiglt.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtxggzrble.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtbafsbwpq.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtfcvvzrki.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtdtkdsrlq.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtvhjnfluy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gtgygrsago.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtntxzbyix.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtgphfvczi.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtbtccbqsv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtvwmciots.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtwykrelhg.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtwwyibmix.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtjtwzddko.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtgnlyanbr.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtuozukhne.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtsoanqqpa.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gthpzkwckd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtxwvkrwfu.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtjtpzefrn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtpodzikfz.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gttbxwumxl.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtgmmuqbxv.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtgmwuzthe.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtmffrgdbc.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtnfhgnnog.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtvwelqemu.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtrpalpvtj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gtjwdqlqcd.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gthscfymhj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtabdjvxbc.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtczpfpawe.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gthpkvqbif.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gttwoqeiuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjwrrfkig.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtbvfjzmhu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtiddskils.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtorbheqaw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtvxtcnaey.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtjgxilqzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtkhltlozc.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtwkkelxgl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtjitftbwd.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtfeukaets.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheiyjrjf.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtxutsbulb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gttcakwbkx.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gttlzvjwum.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtuqvggoqw.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtxslrmpfp.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtksmysbie.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtyjtkjdym.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtqjdtbyic.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gttuemqhdf.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gtrgxeyvew.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtlywomupv.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtsyglgyfy.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtzwbhrisy.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gthfosshph.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtgkmwxoef.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtkroyvxei.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gthotqhpig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtsemyzldh.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtooyaqkqn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtoouxvacz.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtnsasqjst.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtjfjpzljd.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtcxoeixkx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gttqskwoyu.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtjugsnuqs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtaufapcqj.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtwltuaoyd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtffcvuarc.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtkyzkfpow.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtkcaauqgt.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gteiqsaybq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtxplqjgte.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdysbwjzm.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtavlcjbev.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtigxvwgde.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gttivhmyze.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtefedyofp.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtknmeztwm.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtdzveglar.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gtejzsuaxe.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtwklhrvpp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtsebgwrkg.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtwdcsxkfu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gteaufrhrm.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtziyqmhkr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gtrxwbvmpj.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtibknumio.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtqkkuiqdy.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gttywfgbrq.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtstaukmtp.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtbvimyuxp.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtywjtxzki.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtqbastnca.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtadqgzpnt.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gthkdsdpsb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtstiblxbs.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtewtcydhc.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtucsqsczx.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtoesrrmyr.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtkdwtagpb.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtfevwbbgm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtvpfjcwfs.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtgoawivdw.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfifvroq.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gthpeazxzk.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtemsfgnyv.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtdqjrhogw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtykohgwnh.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtwioedyza.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtsiiwnsof.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtqnrtgbuo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtacjixgsx.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkukpxscw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfznsfzn.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtnwqmbptp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtzvrgwwjw.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtqdciqosg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtdrmxfdno.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtaeisndoz.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtttlvvfkf.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtebejhayp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtgrvwywle.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtypbmsbtw.html


<!-- 参考信息 -->