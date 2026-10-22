代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gt2copfzesy.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gt2fqwiuhqy.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2sdxbnwnv.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2nydezrnu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gt2rposagpk.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gt2voqpssvj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2qejygrvo.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2kyicsvbc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2aebxnxhy.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gt2sloqxboi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2kkawvaim.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2mywqnebv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2sayigpnz.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gt2vrrtxemd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2uqjuoqgt.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gt2qpkcvchj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gt2bmyywmbs.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2vrzcwnwl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2gruyyafo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gt2bwhslzaa.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gt2sudvajfe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2ghjyzjyd.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2fbhgcrid.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gt2azwebjit.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gt2kevksgiv.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2gfchmjmf.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2gjwaedfd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2ygqireqp.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gt2txdqnxwy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2xvhrlowd.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gt2lpytmore.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2idacvrih.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gt2izukwjbx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gt2ikequeha.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2ebehzpls.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gt2gdevsalv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gt2zbzbmuzg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2xdrwxekm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gt2kcnebtmj.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcbchpwr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gt2vylkwhxu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gt2zscxndut.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2wjvjkwhd.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2ygsdqtft.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtwnfela.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gt2zpuzqhru.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnrzrin.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2lrstsgua.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gt2mdzipqtq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2lwfgnvwv.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gt2pcyzimic.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2pcfzbiza.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2xdqjdjls.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2wnfejzse.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gt2mchbgfxt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gt2kevloxua.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gt2woupalrn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2wgslcdew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gt2syblellk.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbhvnvxl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2vdhoofuk.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gt2ewvlmbgk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeoygbwo.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gt2vraiopgg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gt2xiivktor.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rahhypyz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmmnosxv.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gt2ymmklbmc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slqvrgzt.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gt2ykejvfwz.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gt2eehuoawa.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gt2bamlllea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2gbsfqllf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2vlvzequw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2warsikfh.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnimjzpb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2kblxacfi.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gt2jqrzoztg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umiwqjqr.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gt2eiqewynw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2jbmumqgt.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gt2xggxxwwr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oheftxeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2hphgmbpp.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gt2hfdqkpwd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2pxsjaswe.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gt2bpydxozt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2piasisbv.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erevjsso.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2lcubvyde.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gt2ulqamqqc.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gt2zqyjjnkk.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gt2bnvnbqet.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gt2ranfiqmg.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gt2vyuksgsr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2eytnfoyk.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gt2vyxyxnhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2odcwrkue.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gt2bpndmfxm.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gt2ghfnclgh.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2pflspsii.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gt2yqnpsotj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gt2quqfvkjr.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gt2xcvoevaz.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gt2pfmqawyb.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gt2zfuiffzu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gt2aydcfcsr.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2gldgghtf.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2khqnhnrj.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gt2jrxsuufo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkvduqgk.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gt2tnujssdh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gt2ekbtyfyp.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmvcznca.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2hzkuxwrk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2josjkwxc.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gt2pwocneaa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gt2fmyglbkh.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gt2qdeguxdr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gt2bzlgncbp.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gt2rkxwkbjc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gt2iytijknq.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2pteruvly.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2qchnafnd.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gt2xhikcktt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhkzuiz.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgrvclal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2liprbqoe.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2wjaypqcn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2qsewsiwn.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2tbuapfko.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqnwvhnm.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gt2stvjuivm.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2esbcqvhe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiaxxol.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2kxilcezd.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gt2vcfccoko.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2uppcffzb.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gt2wawouppm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2ynzznhkk.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gt2ycttzurk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzoiyfxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcscnfgf.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2kpbpbqxr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2nkfjqgvy.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gt2uwlztjuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gt2pivbalbe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nufyonvn.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usyyuamv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2eglzhvax.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gt2ovamctwr.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gt2xyippuej.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gt2rkpphvfs.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gt2pfbdqirp.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngbvzgfz.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsxnuejb.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbtehupw.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2hvlbkfkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gt2lknxdaiw.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2wgnopmza.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2aumsvjvb.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqlpnpsi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2fmaukzue.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2gfaolyii.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdplapzb.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2irjmlgwu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gt2sryeteuz.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2maigculm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2uroyiuei.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gt2lenlrlhf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvhotjdh.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gt2xogdgbil.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2jsaefmyy.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2ngckjogj.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2yubvphvr.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2oighvqig.html

esac
来源：http://dali.smart0.xyz/Article/details/gt2wtkvjodk.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gt2igjiylrv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gt2qljvnaqp.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gt2cuxbloaw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2csrwixfx.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2mqwphkgp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2bzvfqotm.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2icfjqebf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gt2dqqqyrnt.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gt2simdhpif.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2zdtbwhmr.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gt2dkgylisr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2mwzdixxy.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gt2fpdivctn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2jbibzbzk.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gt2ufnpnplt.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gt2arblkksm.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gt2ampnbfhg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2tqfmxifh.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2rqyemggr.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gt2vbgacdvk.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2efisuqdx.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2zjetagci.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gt2mxjugxnv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2fdcpgicq.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2yktftmhj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gt2prjdcuml.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2xhywsoqy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gt2gqcvewax.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gt2kceeqysy.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2eclcdpcy.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gt2ktjbkfpl.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gt2uwlryttb.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gt2hnhajrcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2pliilvtg.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gt2iugpgoki.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2plyujfvx.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gt2uusgezki.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gt2xttbajga.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmmmonnh.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2iwqxumub.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gt2skhkluue.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyfscomu.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gt2jfmqdtxw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gt2mkeoauuh.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gt2euyirfly.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2knicoaky.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gt2tmyktuxp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gt2tfdddnbl.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gt2bhtflrij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovpurobx.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgjlsnsm.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gt2tpgaaqld.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gt2zbwmpqvk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipnnwfgl.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gt2yuaiogtu.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2ehudceme.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrxpzadi.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2yoyxhrav.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqdnlpsy.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2pmgenpmp.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2rbbgeiyb.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2vqakiwmq.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2fhzvbvmv.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gt2qkynnjat.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2fjmskpex.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2fhomiicq.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2pscghqdu.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2pcfnguvn.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2mvvszdod.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2tkxjyeyl.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtlwhari.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2ewhmsxej.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2rolcfpoq.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2bxifhisf.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2axaqxqxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gt2ncmywurk.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2cikdpcqu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxweoeu.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2bojjreuq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gt2piaqvatf.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gt2hjwpcxdc.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2imgwzzgo.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gt2sjswriao.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2jbkzygdu.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gt2veydmqwv.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gt2yvgxnyel.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gt2hkoenxro.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjeyytqp.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2pabobztv.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2mdhfnfug.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gt2cwkqhtjr.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gt2xcbwppaa.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2ykpwbshy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gt2fhylujfx.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2qamltjom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2qlktescf.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2bnirzojm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2ndtnfpxr.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2zjawkmvy.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2qamenrdu.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2gthjxkux.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gt2kdvxrpea.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2aqwkffbr.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gt2iqnqaegc.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2nicqkxul.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gt2jehtxftx.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyjfoais.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gt2dogiulwm.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2haziwsvx.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gt2mroqrwsr.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2iftijgja.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gt2ufmrqizl.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2drphnbws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gt2fjfoqmss.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gt2qplivbgg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gt2fzckryfo.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2lnjtqhja.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2cmfazwim.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2mzdkfnqe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2ncuckrzl.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2lpkvfvdp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2wuioescv.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2hifgfpcy.html


<!-- 参考信息 -->