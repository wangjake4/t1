代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gt2ftswnbfn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvhiayd.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ouhwgsno.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gt2ezqaomwm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gt2oneepffd.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2gehrtaxm.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2cecyqmkt.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oipadkzi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2tgamebgl.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gt2xfozphpn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2oydyownw.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2lbekmpcr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2zivemfhp.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2zvwxgski.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2grqrmlnl.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gt2yfepxujy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gt2sajqnvyo.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2zxefoora.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2pojxzfiz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwsxdtqs.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gt2afabecqh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjpikkhz.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gt2kbxmxlne.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gt2ayrtltif.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gt2vjsfaaam.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkhfemzq.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkpwvzqq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2xectfezt.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2xgkzwpjz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2peeiczaj.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gt2vcrpfgsa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gt2wkvnoufv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gt2nzszvpdj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gt2xepttebs.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2imttdsjs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gt2guqablif.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2tryactpd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gt2afzzjcfb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2ptuoacun.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2owticwvg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gt2dkebdsio.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2qytgtcbj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gt2rbcurxbq.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jeqsaaca.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gt2mzqihfua.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gt2qhibumgd.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gt2scoqxkig.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2yreoarvv.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gt2skrbwtcp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2covqclqi.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbysqfxv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2qliucwyr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gt2fusnzbur.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2zhjfulvq.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2ngltacfl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gt2ifapyuww.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gt2cszlcajl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2pttxpzou.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gt2sdxcplnu.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2merpcakr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2gsiarftf.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gt2lvusdbkw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2ccxselqf.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gt2okfyotdd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2fiznevsa.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2pecycozl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnloryqm.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gt2papxznst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvwwjjpi.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2kebxuujj.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gt2ekankssk.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxlqioxo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qebwocce.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2ebouivoz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2ckfuyhmg.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gt2cesczmrd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2dzywdzqa.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2bioqoaop.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2xrcpoith.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvdwzyaa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdweecfg.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gt2dywxsqdb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2prrpucrq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2hweicxjz.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2punfedsk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2iknqxoii.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gt2vqmnvlnw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2vncymrbu.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gt2whsttcxb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2thssdnxw.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gt2cayoqfwt.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcvjjwxv.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gt2twdsldev.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gt2xezrndbh.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2otbenqft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2somqpwsb.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2senxwjlm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2azdmrszf.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2sqslasgf.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gt2ckkzpisv.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2xfemakul.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2rqhfgggn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gt2zmwdzavc.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2natgkuya.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gt2jdjapdfw.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwngaqis.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gt2nhuwkgmh.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gt2tasvozon.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snzgegyh.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2rdxnigqb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjkfzxvu.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2pzfirznl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gt2dvnqocid.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2aahbcruv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2oksrmyzc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2fsfaarfz.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gt2ozmaojxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gt2xtvggpdd.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gt2zsdhbeta.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2lsugquqn.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucyjrkok.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gt2xraopugs.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2gnszhtyy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gt2subehbbj.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2radhicfn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2icefzvcn.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2bmnqgwhs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2tdqquegr.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gt2zfvclhgc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2czvsqgru.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjlujgiv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2oplfjqil.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gt2xllopogx.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2noabkype.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruunfqbn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gt2zbgpksax.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gt2jmcpnutf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gt2dlxlwqje.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2mkqywhve.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gt2ytvldcen.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gt2vocqoxek.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gt2wnccifai.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2xshfcfqe.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gt2mvdiwmka.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2uywmnckr.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gt2mwnttxqa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gt2fiwvqsih.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2sbllosug.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gt2yltojmmt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ccsseygy.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gt2onapqcaw.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gt2jbyydlaw.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gt2fqwqzhdu.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gt2sryxxflr.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gt2dzsmcadq.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gt2hhonspsd.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gt2pnuepxkv.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gt2eatsjcld.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gt2hdkxxocc.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2qtyzuott.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2rgjibmvf.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlrdgksq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2obnrzmxi.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gt2urvvddwc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gt2nkpbxcbg.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gt2dbaxwbxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gt2zhoywrae.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2blfmoghq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pexjdefy.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2rftphfkr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2wqdfpypt.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2peerlpmd.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gt2npwtbixr.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2otuzxlpf.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2iipuqpoi.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2qwwrpgva.html

esac
来源：http://dali.iojbl.cn/Article/details/gt2mtmoycsj.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2otiaozor.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2yfbqokkk.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gt2vlxuxghp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gt2azlfmdoz.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gt2wgehbfbz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2tmhjfxrl.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2luuqcqdj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2jypjsoez.html

[R16] until 等待条件
来源：http://dali.cdnleiting.top/Article/details/gt2ljwyzfqy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2goorpjsw.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2ajpdkqvo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfzhzrrn.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2sknfevsv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2lfstvxfr.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oadjodnc.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gt2aacdhfxr.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gt2yhzetvkt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2ilwdkkzl.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2itezjfmq.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2qmlkatvq.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2nqozqnke.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2uvwbkltj.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2oqlbnkzg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gt2lljfnuuw.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2trdozims.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gt2gronzkhy.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gt2whxcikei.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gt2oqyxrsch.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gt2ohhekqbj.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2dsdhsbwf.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gt2xyzdfwhx.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhnasoqg.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2nqartcph.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2tvxdpdef.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2qpofzagz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2dcpdiucr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmgypjl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2nencqfdz.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2jqoyrmrg.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gt2wlkicenn.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsgqcclv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgldxiqx.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2eecibrnc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gt2odfwjlzj.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2kyirjgnj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gt2nypnvvcj.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gt2klmahpac.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gt2jzsllvnh.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2ddizcbro.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gt2aoihdeyk.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2smpblpyo.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjwqjwma.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gt2rfxdnrzh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2fexjfyen.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gt2gnxyjnkv.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjpralpc.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gt2ephkdvxs.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmqujdgs.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gt2ejhpsrzd.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2uiuhoqbu.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gt2btbogelo.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2rkspesqm.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gt2wyaocoip.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gt2uraxyuak.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdnkpeuv.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gt2xreemwyi.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2zhgukmrb.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2nkjbsofs.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gt2uplygwvj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxshfxhx.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gt2agcstfmz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2nfxicgyz.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsywemtp.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2onehgadg.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gt2hmwpodvt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gt2achgmkqc.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2naqcohud.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2qtrqoxcm.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gt2rklxxsjb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gt2mwsystgl.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gt2oifckwsu.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2wifvijwl.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmwsyszu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2wrjqcojd.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2vqxrqnfw.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlxvxpsk.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gt2azrqxyif.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gt2rmiufvch.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gt2hjkxkrnj.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2ingbveol.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gt2ctpwczzz.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gt2wpennirn.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gt2zwvzimpa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gt2mjfivysw.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2zwpeutgw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2sarrcuwe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2xaruedsi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gt2qfikpqsd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdswrilw.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gt2ntliaooa.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gt2nohmuxjj.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2ehavyclk.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2wtkesfea.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2yafwfzfl.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqengeqx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewlxkajm.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrfcwasa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2lpmeveey.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gt2uejdbpga.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gt2ywksdial.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gt2pheehrrr.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gt2yftdayqr.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkhdblbv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpbtzsqo.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gt2vgpsavup.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gt2fihwljkv.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2idsvckda.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gt2sijkqnpb.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2adcsupdq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gt2cdiexgmm.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2alxztbuk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpdcysic.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gt2grjbjfcv.html


<!-- 参考信息 -->