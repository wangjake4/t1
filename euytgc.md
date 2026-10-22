代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2llfyjryq.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gt2iatcizhk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2aznwtilf.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2plkmzjfb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2dclntocj.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2otkcidmg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2iyigvrzh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gt2xniqkiuq.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gt2taxibaxi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gt2idanawsw.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gt2menffxvo.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gt2vgdtjnqt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gt2dmkchnhz.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2nhckklip.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjdbksps.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2nxsaiymo.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gt2gfbbmfjw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2kvamcetg.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2vracjhpv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gt2qleudfzj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gt2knalnbct.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqwhpicw.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gt2nuvwfsat.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gt2ccdxewws.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gt2iuiefjsp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhspnlxt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2tsnatind.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2chbntmuu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2zadrewsi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogewoxfe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gt2enkpxbzc.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gt2zecvkyki.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqdipkvk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2cbmututb.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gt2falvbfwj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gt2jmgulycz.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2zbmovgcu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gt2caahdofo.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsvlglti.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2bmovjhwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2tktnvorc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2rnbobcoy.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2lenviwpl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gt2kfefthwe.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2lijteeez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2srvyqmfu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gt2mqxtbwvo.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2pxogqymz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhpczdie.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebzbwmnl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gt2uxsfktdc.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gt2fmaaxyip.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjboywi.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2tskbxhvc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2kcpevhqb.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2oabwojls.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2uanzbqry.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsnhabm.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gt2pciumwoc.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gt2lrmcsvxl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2yvqqgkmo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2hqabjoht.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2igxkwesx.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gt2vdvgmmqk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ixexudxl.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2pwgwlcms.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2zedausuu.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2neljnxty.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2srcdvoqr.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gt2cpmvdkkr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gt2midunmqw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2fawgmxnh.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gt2nwlezcmd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2zsynoiuv.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gt2wtpudhnh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2raskyqno.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2rzczscjs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gt2htjrzjlf.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2cixrzskd.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gt2kxuvbgmz.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmuewmph.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzccwvxl.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2zjhcjdig.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gt2rechzguk.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2ioasifyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gt2uklcbyss.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gt2obtqchhg.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gt2kdurzskv.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gt2ssjhbcbw.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2ydxaixhu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gt2luttcwmk.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gt2ybbkgycw.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gt2fzyfkghy.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2ydivjuwc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gt2cnhgntwh.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2rniscjgo.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2xyrpkmyj.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gt2lvtbadqn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gt2mnkqfajx.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2ueudtxpu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2atekoeen.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2wqrdbjyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2mvhzbrle.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gt2zgfoxocj.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umsuiadj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gt2bctvbbht.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gt2cljymeha.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2ssotgnru.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2yuisrelg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gt2mrnlahxr.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2sdpznwar.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsaorfgk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgksclh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2uumvcqqb.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2tzltazfk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gt2geiyaajp.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2tzfbhrut.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2efpyhxzh.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2yiirzrcm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2hwrklbbz.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gt2jldwomuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2xuwxksae.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gt2fitzvwxm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2gnjkhhmj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2easesgck.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2cvkepnzt.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gt2xhoiuynx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gt2jvrtfbvc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2irfsknne.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2bypzlwut.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2vekcksye.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gt2dwypglcr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2enplosje.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2bdsqbgss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2epxbbvpz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vqfmtlbk.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2haxyluld.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnvypnni.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2jalwozwb.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gt2pomokujx.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gt2ubmqtuek.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gt2coovzwdm.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyhqqrxh.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xljmulfh.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2rrrbrwyo.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ywlnyjmr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gt2qwmzhqyk.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gt2qfiacvuj.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2jbxznpsy.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2tneushto.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dfwudeok.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gt2dtqqkivb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2ehmpogxc.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gt2eelsqhap.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2puqangps.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2vjtqhdoi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2ppgexyek.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gt2dljwzdyo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2egattpjb.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2csuhpkny.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gt2swafjaur.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2hyyiixpo.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2stvxvpyf.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gt2mlntovrs.html

esac
来源：http://dali.havefunace.top/Article/details/gt2hbputsch.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gt2vtpttpgc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gt2qpbzpxbw.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2cgnnendg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2lkuzbyor.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gt2asekaurt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2qsxbjtnj.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2vaobpzpi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gt2czpwrjfj.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2aitgtixm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2otmphefh.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2kwsyrsnq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gt2duihacra.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gt2zqqukeiq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2rborvkfq.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihpaenwh.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gt2mcynndrf.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgcuqrlq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gt2oukkjpgf.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2gvwxeafb.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gt2fippnlyf.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2jxhghbmd.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2iyvkheak.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2wiaiuseh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gt2syrsimro.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2icdtasot.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2fjyphyjk.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gt2xpeppqwk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gt2jqdqtlpm.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gt2ngihgblg.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2dtcxxokh.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2qmbrmpey.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2smtlipsh.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gt2hakwijlh.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2dcutjtyj.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gt2xsavkcih.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gt2eqgghpcs.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2xhwfbxwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gt2nolfodyk.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2lrckrthj.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycemgbvq.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gt2hbccusxc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2fsecewfn.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2fzgimwnu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2vbalkohu.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gt2yuodyyxu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2bekkwqdm.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2tbdbzvli.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gt2ouyhmueu.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gt2cdqaxxcc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhcuuynl.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gt2hxmltmey.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rubingid.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gt2swrbpkbe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2rfsgnkfd.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2snflkkbt.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2waibjcjj.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gt2vuprnwwv.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gt2ihvpcxhn.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2hlxylbgi.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gt2rhdayouz.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2hbjnvyzl.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2tzabfcdt.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsgzwwhp.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2ndjdkzec.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocungbyc.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gt2bmkzkecl.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2trcmcyey.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gt2tdfdefnm.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2fizjqukn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2vzelceqr.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2bajoiljc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2wvbryibb.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gt2plsngpka.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2xmowqatm.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjeylpjw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gt2ucgzftfn.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2wzkrswth.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2mgeprvzq.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2bpqyeofp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gt2cyenzxit.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gt2ojszzkxb.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2ruiwlhqp.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gt2qaquoppo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2uxgfkzhd.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2akpcsthg.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2arrwkdmo.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2cthicgxy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gt2sejcjvur.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrmkxmuc.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gt2dxyxpbcm.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gt2jayxlyqo.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2wdgubwkh.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2wrdjuylu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpqjojjp.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2ifzudnef.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2yumwkmwd.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdjbnbmm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2ilmczeoc.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akzhsztt.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gt2kxwmcjca.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gt2xdtmzgrc.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqwgagow.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2ozalgdqq.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2vxjuaksw.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqjfglfu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gt2kaqedihw.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2qimlwacy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2iqhhubtq.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2fgccsfes.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gt2glvtysgv.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gt2dgpmnveh.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2ubtofgqj.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2bnrydhkt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2hsgtibmb.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2jceqiajv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gt2ozpkhdzs.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2fuznpuni.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gt2ciodyyqy.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2ouqrxzte.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gt2mmtecnif.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gt2pylduats.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2wibsoqwv.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gt2dwcwwgrg.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2rljobsni.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2ljokcdfk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gt2dmabtbpt.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2ngiomxjo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gt2muceimok.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2hsxcfoff.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2dvdjpezr.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gt2xzsodfhj.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2myfbcqgv.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2ttcbznqe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2wbtlqykr.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gt2gqleqetm.html


<!-- 参考信息 -->