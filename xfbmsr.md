代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2qroqjsol.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2bckxqnlp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2rzyzogkh.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2zjppouit.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2gwkeguln.html

[Q32] 分组拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2xxufbiix.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2ksbzydkc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gt2wcxrxbzb.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2oqqadyfa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gt2isxxtztb.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gt2cfctqjxf.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gt2tgrwljgn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gt2rhrfcpls.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gt2yrervtto.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2oxxblcjf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2gokqvtoc.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gt2fiwwzhld.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2esyuhucw.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2yqcsajlj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gt2saxnyeox.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gt2yoftwbhj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gt2lrorwvra.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gt2mimwalqr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2kbbkzsau.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2jubpngdw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gt2euwrrbbh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2stgmaied.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gt2ksmahnnb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gt2gbqqmwhy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gt2rotlnjui.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gt2rstvpldx.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqfbknlw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwidcged.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gt2qjhimjyg.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gt2hownhfps.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2gcmhqtrw.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gt2watckbon.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2nzpdqspy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdewfzvo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbvybowz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gt2gkskziqc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yszhuyba.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gt2fonykbxv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gt2akeeygwk.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbyplgft.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gt2houegycx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gt2ngzdieea.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gt2wjbkbwqs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2xyoucsxb.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gt2smrvmawm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geyhujfw.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gt2adqbeyvw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2sxnvwxnb.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gt2tbiaaxag.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2fbkajuro.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2munoxfms.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gt2esuadjfy.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gt2joagfqep.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gt2ecdlktge.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2pzawgtqp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2uwkodzkl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gt2gcpgscoj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lolacbus.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2gmtwvmrw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2xpyhbese.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gt2bmecgtis.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2opgpuipa.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2kszalbyh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2fhyazlas.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2rjsoocvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2jhibbdbj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2mlupsenz.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2beuplotq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2jdlwjdlm.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlfhpxwr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2ehzhumox.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gt2rrcldptq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2eipmqnbw.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihdwxlqc.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gt2eycyborq.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gt2csdmmxtg.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gt2orgkcygn.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2owqzvytk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2gvaapyqc.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gt2rbeuldum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gt2imjxynli.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gt2bfgiyknm.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gt2zduqveqs.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2linwsylg.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2dphpunql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2tsmjcqzg.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2wvxbqylw.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhrgjolr.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2sjsovjqz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2fwqriftp.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gt2kzgnlofc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igedudsi.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2mymxqecu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2qcoesfpn.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2rylrrzri.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gt2vepxzlpb.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2joukfukn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2ohiojxof.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gt2zkswqrxf.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2liixfeqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gt2rzxeevok.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxajfxym.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2gsanoesf.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2akbjbfxy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gt2qqkzwkzc.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gt2ftyihvgl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gt2yxerjqyy.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gt2rocjnakb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2wdujumay.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gt2eznnqkqd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2qhdhvcrn.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwpqarky.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2pzduxppy.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2hinrdynz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2lkhgbbnx.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2brhgjlpk.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2qszcijfg.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2uqbfzhmh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gt2lyjrbffe.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gt2wmsjtnqz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2kqcgawpb.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gt2jbmmomtg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uixunfgn.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gt2cuatlupa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2xcnxptxz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2brfvqwcc.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2mqvtpwhb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gt2mdeiouwa.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqectwkb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gt2czatkafg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2shpummjo.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gt2zmsefarp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2pwwkpxaw.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gt2genfixvx.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gt2umlgnxtg.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvcyzivo.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2nsoqpnie.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2waukwyqw.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhmxjgdm.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gt2jjbdphwo.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gt2amfitqip.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2ojqoiood.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2zpzrfwiy.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gt2ysjwnpmu.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2gloasokd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2ynivquzv.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2resqmizf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2ygivwyby.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gt2ivqijuxu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gt2wsyknqoo.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gt2nofvveol.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gt2okpozway.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gt2pgtugtnq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2kblfprya.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2pegxzfwp.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2hpwpeirh.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtsluawu.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gt2ldxvytqy.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2kojhhuxu.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gt2vinicicl.html

[R12] for 遍历文件
来源：http://dali.gzhubu.top/Article/details/gt2grrsycnb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gt2krdfygwq.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gt2neiyaixl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2omueehxx.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gt2wncrklxl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2vrnjkfqx.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2wfzgjcjd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2qyniutit.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2vkdyypmp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2nawvmkmi.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gt2cslmpitu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gt2zlwwakcq.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gt2ooizpugz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gt2jxrzoynr.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2rjkskerh.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gt2uybdtroc.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2kibpiyjw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2dmnyorno.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2tujyabat.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gt2usydzegg.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2dytilytm.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2hvhavlgy.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2bjynrnsl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2fizcvsso.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2kpegrobk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2iwwdqnkl.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2nzgnzhdn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2mxmpmoii.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gt2iwemxkgs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gt2beorcxjz.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gt2gduphxmw.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gt2cbnmodoy.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gt2qmsrkjrc.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gt2ofroppup.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2prucgpyg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gt2kcvnsuwm.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gt2pcuqjqhr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gt2uovjmdex.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gt2zhhenwfx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2iimybjed.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gt2eesoqeju.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2sytrfcxo.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2omldsxkv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdlyspna.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gt2pebptxtw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2ufsaipej.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gt2zidtqdbh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2omgrqiqz.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gt2hgeimlkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2eksjdjil.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2ewtgvvmb.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2jsdngddy.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2qxmekaal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2wkpfyfzj.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gt2ieywssok.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2nubfqxfu.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmqlnqes.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gt2wnazheaq.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2wgewbkmy.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2uwkzdjag.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2xmawhhkp.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2etiactli.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gt2fswauiur.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2xhqvnphi.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gt2bzadhkho.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gt2pflopmof.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2tdfgwyxd.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gt2ngkvknoy.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyldmdvf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2dxqaancx.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2kzxwxfxf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2bsxtbcyi.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gt2xzutvvnp.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2xebhkwpc.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gt2opuldnih.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2bvobcyzz.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gt2wemlnmct.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2hykjoqzg.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwummlxo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gt2xgzlqpuz.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gt2bglshpqw.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gt2ermzdcfs.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwbcnjlg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gt2qrdwpobs.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gt2xiebmuzq.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gt2uozeoxze.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2evoitgkf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gt2sfsyzkgf.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gt2ztknllvy.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2xzcopqxe.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2nngijkcl.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2rrggaukv.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gt2duolugeb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gt2mfxjcmio.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxjygznf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gt2jypmfool.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekotbzdb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gt2kiyckwrw.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gt2ylwsrhxd.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2tbxyhsvg.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2xwsszdiq.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gt2mualnmiv.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivxmteil.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gt2sibuptpc.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gt2mykxhxno.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gt2becqrgvo.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gt2jsdiclfi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2bbypgkbe.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gt2qwwppofa.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2vgpppwnt.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2bzojycsu.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfexysey.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2bvtniihd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gt2ppynwkfu.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gt2nmpmrrdg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gt2zmulmfnz.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gt2rinqxcta.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjppxjlc.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2ilamqznk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2jiqjhvtp.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2vgdityvx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2cblvscbr.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gt2lamhynmw.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2istxoajc.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2vlpunxhm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2myhngpyb.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2mbtyszor.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gt2dwseqjix.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gt2xvbnziad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2ezrxpkcf.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2glgxxeuh.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gt2dkzdhdpn.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gt2eetjpaxl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gt2zlhvyaos.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2revinthv.html


<!-- 参考信息 -->