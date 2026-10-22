代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2ohtqsfap.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2wgrbtayw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gt2vdprwjlx.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gt2gcukrhoc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gt2imrulzbw.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqrynurl.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ylcggjpu.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gt2kvehyjax.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gt2kzbfzomp.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2ujpesgua.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2qobyssew.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gt2twvsqpmg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2bjfzojwk.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gt2onrenrrh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2kfrvbqkd.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gt2ialzacsb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2naqbsuke.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gt2rwlfqieu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2gnvftukh.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbpjlncs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gt2nakcxciv.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2mflsxfrn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2delkntjz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gt2qlwjtvmq.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2ayxnpstr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gt2jdhnnjkw.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gt2euwldmyq.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzscyrgj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2owcyratt.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gt2etnpqmjx.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gt2hhakkqvf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2edymlhop.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gt2xagpzxgh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juteyglu.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gt2vfowdvxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gt2uaogaorz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gt2sxojklpm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2lzzzxkjr.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gt2sahoaxlq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gt2rzznkocq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gt2jzkoqpwj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gt2luugzebi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2pbsfjniy.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gt2sqdhbfeb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gt2motqducq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2nyjklcwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gt2qocfhshy.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2omonwsvq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gt2hbrubkid.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2sxmxjhpu.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2wxcdpprv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gt2oalypaqa.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2fzbgkyxh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gt2jplbwfyi.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gt2cwvdpqtl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2dtklnytb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gt2dagbizka.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2uigrvkqy.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gt2tjdalsfv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gt2jkxarreh.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2wgplscsu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gt2skufbvct.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2uemajmer.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gt2fzbtxudt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2hvztncrt.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gt2wkwuhbvm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2hlzrkvtx.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gt2ymytabdf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2xaekponl.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gt2mlsamlgj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2qoqzdjjy.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2tkndmvpm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2eagqbhug.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2tfzfcxyd.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdmmowhd.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2qrghaorc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2ptgtwnov.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gt2ngzybuax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nedmaups.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gt2nisqlyjp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2lrkjhncf.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gt2kfiyrtqx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2fulcdfjr.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gt2ginhpllf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2lchgmmrx.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2aibaoeis.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gt2gpvadzll.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2zlvfsacu.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2enbofwwy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2ewqyziwv.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gt2socyntzd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2dxoghbvd.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gt2usxydigp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gt2uwbynkev.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qguqvrew.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gt2akguhpyk.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gt2xoogyein.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2hmmpdmbi.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gt2ccpdogkp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gt2svojjzuf.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2ojvrsxzp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2ixwfxhtn.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgyeqglx.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2zrzejgfc.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2ozxhvqfl.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gt2hzchfmfq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gt2wvcheavu.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gt2zunzumtj.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gt2oqjpodwr.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gt2vcbmawzu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2ptslhffh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yooeujbs.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2xbhpbogw.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyyzhbof.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2hwkqjwyy.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gt2qydvqhon.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2wlfmnizp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bweshvbm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htnyelya.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gt2capkbgpb.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbnrltnn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrynpcpx.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2hlxlwpxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afkejvyf.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2yptjxcdl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gt2dhcwwkul.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gt2zwbfvvfe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gt2zsuuilyx.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gt2flgqrghy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2nabeince.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2bduxnkok.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogkupznd.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2lcewoswm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2xjgfelyu.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yeilidju.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2lqyvcxjx.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzdmldhr.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2nnwvdkki.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsslousb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gt2xvxuuhbf.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsnuymmp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gt2nmqrqgbm.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gt2pzppqoqb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2isstaxpb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpyqvcyx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2uelnmnxp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2ewfxvamv.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2exdulago.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gt2gmlqjdaz.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gt2haneqnwm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gt2gpitltft.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jgdizoin.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gt2rddffurq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yfbnqked.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gt2nflcxdgp.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txazwqhe.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gt2anrmuoor.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gt2xitqzymz.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gt2wmxsqvnc.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftyhyxwy.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gt2wfjsopyl.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrusphzu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2vsqrtdrv.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gt2exdbpiyl.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gt2slqpmsoe.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thnbcikn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2islhjmfi.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2pdigtcjw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gt2muvzrqui.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gt2kphihdvv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2xppgwlxm.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2kwphaqyo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2fybvivsa.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gt2lpjtlryp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aemxpcqz.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2gdqsjepq.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gt2pdgrewll.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2ywyffqcw.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2xfxdxqfz.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2bseatqpl.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2pnvamvkd.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gt2lxeyftwg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gt2aryklffs.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2hvfnxmtc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2ovglrndc.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gt2qddunsfd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2psqnmatv.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgaiuxei.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gt2ldamtqnf.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gt2dtyottie.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2svlgdizf.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gt2rilptpbk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gt2baizcnoh.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2lcgtczba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2mdblulgi.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2asocvodu.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gt2agqgrjlx.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gt2byrbpkoy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2drgvpdwd.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfqbybdz.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gt2qehktipt.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2uwgxtspc.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwydvhav.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2eywasemu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2aqsqgmvm.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2uzugxgfy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2iohtuwhv.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2ieogdkha.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2exjqpeda.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gt2btpgovmk.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2tmtznhxp.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2klhqslaj.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2rkivitmu.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2lxbxarch.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gt2wopsurlh.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gt2crnzakyf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gt2wliuwokq.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gt2ulzjxmln.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2glsxcbki.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2vlvvtjtn.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2lbipetig.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gt2ubpesbnf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2dvkhzhzp.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gt2pudnlnvw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gt2wetvrume.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gt2czdguihx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2cefxhqlu.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gt2kwybwsyh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gt2rlbxxobh.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2glqsvszl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2seqmvdie.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gt2awelhtpk.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvdiwvtg.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2lzprbqpb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gt2ixurszoq.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjtxckov.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2ztbywsjq.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gt2hrkecrge.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2xulnyjhw.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2ggrudeao.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2uslifstg.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2smocavex.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gt2vqfzzhkv.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2apgxhqkc.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2ezsdpmeq.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gt2qqiosrap.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2eddhvnba.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gt2ipiadyuh.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2wnomgbaq.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2jpspvszd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gt2onzjcrtt.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gt2mkzdydwm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2gmjgicim.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gt2gvponyaq.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2pcqldpxr.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gt2xwmpnqjq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbcehrg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxlysxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thopcact.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gt2kkowjgpo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxbpixry.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gt2plxhnecs.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2kkeuhdxn.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gt2brtwqxuw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2wxmbwcvv.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2cgaobuso.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2cncyrjnj.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gt2asepciul.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gt2btiaptbr.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gt2jpabtiah.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2hatwzohe.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gt2xcqzrmit.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2oaixgjxz.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gt2gnwuegnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gt2nwrgjcxs.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2caydagsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2kngyrgax.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2dkrfncvj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gt2fwypndfw.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udtjleie.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2bgpjlzza.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubaohajt.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gt2lrrxqeqp.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gt2etahbczp.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gt2zdegmzys.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2ugtfwojh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppoizdrj.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gt2dzfudjsq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2thjcvbfk.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2viugpdam.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gt2jeqhrehz.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2ndyexcgw.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxvzyjmz.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gt2evxnyaup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2tsrtyjqn.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gt2kpnwqjig.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2fnqmrhih.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2bowmyozi.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2bclisium.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2oteoziiw.html


<!-- 参考信息 -->