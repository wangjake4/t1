代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2ycsabczu.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2eowfwdgm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zezkmdya.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2shiktsyf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2kqvrrhij.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gt2ildlmmdg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2cbwtqyxq.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2pothgjpe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ixuhmfnh.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gt2ojroiazk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2kmjwmtky.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdvmsoab.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2glsnjokx.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2fnhygmpn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2ewgvhxhk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2hpvchcmb.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gt2fhgkppjp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gt2dvljupfr.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gt2blzmdizy.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2kyiwqcwr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gt2dpfldzcb.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2qmkqvves.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gt2bpnegvdz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmavewm.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gt2afocwyvx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2sjqwfois.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gt2kxygzgbs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jianghu66.top/Article/details/gt2jsurongq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2qohowcfg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gt2ywkpkzsz.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2bnkrlouv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gt2tlpkzgzg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gt2fgkzwgup.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gt2vmfdkhka.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2efjoklqu.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubgstwhw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gt2zqoamyau.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gt2gqkniofv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2dwttgddr.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2reuzmmld.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gt2ppvsksjv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2yqrwcqrb.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2asaeygvc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gt2mkwojyoy.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gt2lwkfebae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gt2doqxbpjq.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gt2shtbjsex.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2viltrkhn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gt2icswhzbk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkegmzkt.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gt2widhdwfe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gt2upjlewvv.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gt2ljluqrhj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gt2vnmapfpw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfckqrjd.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gt2vtoiddfj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2hiwurklk.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gt2pqfbvxuu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2lbmvjgqk.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gt2kehhyhyo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2efjqohjk.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gt2isvdrfzf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyvqamhl.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gt2cvckejor.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2isifnded.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2ooexjhgq.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gt2miohevrr.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyihozvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2rssyanus.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gt2mmpkfgzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2npesjiwd.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gt2qoicturq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2xhynbwlf.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2rzaurhbx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2nhymgghn.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhjsxqst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwldbhnh.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2bgxkvbua.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgfgurzu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2ybbxyegm.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxfypglu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2mrwgfkwv.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gt2zyzspsxg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2afjqwzwy.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gt2aaoeypmp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gt2bowlqwwo.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2nhjbjsdo.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gt2sedbbxgv.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogaxxcrx.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2yvozbpdx.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gt2lfjfegyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gt2sjzqlfcx.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2lyzmgwyj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gt2wntdzvbe.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2osyemgyo.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gt2slltlybs.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2iqjanbye.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2akdnyvgy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gt2fxrlbfue.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2tblfaagx.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gt2mnuoecnd.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gt2swpmctpf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gt2xfjzadgq.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2cakxcxhn.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgkzalbd.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2noovftpf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2agnvddzs.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gt2oxqfwxgw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzntaqfl.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2fcunbwna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2yrvvgivb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2stmsrclb.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2hezglgax.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2sqzwbhnk.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gt2vpsxfmzj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gt2cmjnlpys.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2xsdhosug.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gt2crtmgmij.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhohxonn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2wnjyhgag.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gt2woydnkkl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2gmwthcgy.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2yvpmltwk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2wyigwwca.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gt2xjhmymxd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2wlitqgjo.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2ksuevrce.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2sxqsarjb.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxmdllbe.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2qawqyeky.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gt2rbjdiaec.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gt2xqjxdfyy.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2mrngtmwp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gt2mvhcpjrb.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2kuspgzjj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2hfkhorwt.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gt2fcxnkxwz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gt2avdnlpmd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2wqlrnray.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gt2dzxkvpzp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gt2ofngjixy.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gt2fktgeerb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2myzhdjiu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zopgthbh.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gt2yrpblpqj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2knmlrscr.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gt2dksaauid.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gt2iyhysxpj.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnmnvvoh.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2vycuwktd.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2zgrgtxfv.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gt2fxtzdbav.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gt2sajumvlo.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gt2damtzhlf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2pogasgfp.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gt2ghcuynda.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gt2ahuqqyco.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2fmuvzkox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2jghhsbes.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gt2zxwauqzz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2ucjigdgl.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gt2dqdyfdzv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clvodawm.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2ngblrrwk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrrjctpu.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2skvfixjm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gt2embvzzns.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylqznqca.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2islcbyei.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gt2fpwdmczh.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gt2anqbariq.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2qxassekf.html

esac
来源：http://dali.yj202588.top/Article/details/gt2vzrnfhjy.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2xleqscvm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gt2snvpaahl.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gt2pvzihfxg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2xefcflog.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gt2mgcgfkvc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2llpngwtm.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2vxwezmag.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gt2jpvhqelk.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gt2blduyeos.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2ehpfnnfe.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gt2uediurjn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2uomcssga.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsewkusq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2aexkavbh.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gt2myglxfrt.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gt2wpdfwhqy.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2tonmvypw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gt2nktmktvx.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2kbguqbpy.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2yxauaqxm.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oafmrpdf.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gt2ldxzlsbf.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhaxtcnp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gt2kpkgyqww.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2dreyhuhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gt2aueakitm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2aawaveeq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlcijvhd.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sweebsph.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gt2armzilzr.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gt2kdftytaf.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpeqgjpa.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2epzmecro.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gt2kxclywbb.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2crzfatxq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gt2zlvsgufx.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2swfjbzcw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gt2gtsfcmzd.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2htriwysk.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shrgvpge.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2cxkexukj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2rgizdtmc.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gt2faownshg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gt2iyuzzkeo.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gt2qeqdkowt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2chcqvugt.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gt2scxcacys.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2zdzrfrjt.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gt2pfrhctme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gt2swqhxycd.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2yjrmutxd.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gt2jklrrkgc.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gt2ctxjbosj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gt2yludpoqk.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2ggjflein.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2tirjujtx.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gt2zzwjryvh.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2syhbmdyh.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gt2ufajhanc.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2mletxugg.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfoxposo.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2uirbtdlr.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gt2uccpnchr.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2qkkvvlqa.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gt2jbembwkv.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gt2inuclopn.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2vhcmujje.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gt2vhapyhas.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gt2ylqqpbij.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2laesynsm.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2dibmqkqe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2jptryhvy.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2dwttsljb.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2vtaefiqw.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gt2fnjbunqf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2syncfcbv.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2xgsozuvp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2nioxnjta.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2wypxzcpy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gt2kegjqioo.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2uvvunchr.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2jfrdnlfq.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gt2rogucmoq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2xynripjy.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gt2uzskqluf.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gt2dxezrdmd.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2qqfbaxpo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2vorrjimb.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gt2beysfjof.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2dprbsidd.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2bqilajua.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gt2pmaauqna.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtkwmpts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2skescyjx.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2dnspvliq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2jazzruxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2yyubfuga.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gt2cyysakgz.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gt2zcvmugaj.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gt2gxgrewvr.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gt2hjtaznuu.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gt2kyckjjtl.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gt2tlintztk.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gt2uscrerdo.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2gyomwfak.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2qlciwnpj.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2blivvhkc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xffccyhh.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2bkzwxopv.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gt2yvmwfecr.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gt2xqianjzq.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gt2hdllftmt.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2skbongos.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2ptdvbgiu.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2eeputydp.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2mtzqgigp.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2nuuiocsn.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2vcmwltmy.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2ucaicfly.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gt2jjfjnxda.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmyrqbzc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2iwdknuck.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2hhloawas.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gt2yixegekx.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gt2zeygfszo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gt2mtqiosds.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2fmakpgts.html


<!-- 参考信息 -->