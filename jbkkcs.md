代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2dmghpmlw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gt2zhyxtpgn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2firbdqqv.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2kevjfvsv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gt2gdpfdnkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqpvnipl.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gt2dpuinegc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gt2xzhznxhl.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2mwvxhvno.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtjdfkpu.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gt2xbhzddgi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2aoywgzbr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gt2wdnccgms.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gt2rcdxulnx.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gt2dborsacx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gt2rvcujlzj.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2vdshvsxc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gt2bqksqscd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2cdhatfll.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gt2kuoogwms.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2asoqtvol.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gt2ptalmmkb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2mmoiixgw.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gt2btwngdti.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2ifzvvdip.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsnbhhxc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdwsklsk.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gt2hcinrofv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2ihkjogcc.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2ysdjuqwv.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2yknotlsn.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gt2foparqcx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeurzyku.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2amzqszmg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2eovrxhwb.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gt2qlqsekix.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2nzfsqdvg.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2asvdhpmi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2fnjhczjv.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gt2ndgkivvk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2tejxmero.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2tneddvir.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gt2ezwgvpqw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uneueuqu.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2cqitzcog.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2helhcxnf.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2mgbvxsff.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2bsnrwkel.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gt2zndgeqpz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gt2skaersyy.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2ccefxvdj.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gt2mgcvfbtp.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgbzzfxz.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbppidvc.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2korfahyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywtoohfv.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gt2twyvzkie.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gt2cdhcckxe.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtcbucmh.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vklalrwg.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2vcigtqus.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gt2qmptzggt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2kxpehfxz.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2nybqimaw.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gt2llmsnrsq.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gt2xqivwebg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gt2sozhnkqc.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gt2qbslfvgn.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2radugbfm.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gt2colgqlnq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2gejrdlfk.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gt2lgpjwuqg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2iyqaeras.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2trdxhkiq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2xmqvaouh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2qflnqfrn.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gt2psyvaquh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gt2qazsgysy.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gt2jxhvmtcs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwxinjad.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gt2txzzmzgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lycaqcih.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2qvjifgga.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2wjafrbdc.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gt2kqjlxgnm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mepdsxht.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikantare.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nycdpnwv.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2wkckyocn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2wrxgnxwe.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2cakohgwn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2lgfacrov.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gt2tqbfkcxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2qhbynmhy.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcwcqntn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gt2horxygse.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2ebnxcvfn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gt2jnafmnev.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2eohzougf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2jkxnfbai.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gt2vhtjviaj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gt2ocfnlcwv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2lmymmouy.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gt2plrclqmg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gt2diuoamrv.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2kfzwhpeg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2apeormnv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qcxlfbko.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gt2ojavuxps.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hkubzpjf.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gt2aoxzffkw.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2kxxvyhsk.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gt2ktjerylx.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxhpqard.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gt2qdfhiwiw.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2peczlswt.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojjgtxlp.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odynxmnw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gt2zcxeemvk.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2knwakfaq.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gt2ztcvhupf.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2avjgbesc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toorbyts.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2mxsoiqex.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2ivqtgqdz.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2pccbqzpa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2zazndaek.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2kvxrypnh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2lcvwytbc.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gt2fktnevah.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2ejuocloe.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gt2teihltyo.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gt2tjvgkfnd.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2asbvklue.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gt2wraqtutm.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2lnnpfuwh.html

esac
来源：http://dali.yuxming.cn/Article/details/gt2bhzzhhqe.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gt2exffrpbl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gt2poqqzylh.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2hzmecvih.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2sulywodx.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2ijyqrpfj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2gxmqaixy.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2vcbbtncm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2xmltyxrz.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2nsysufeh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2vicicnea.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2tocswcsa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gt2rrpzpnxy.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rimdpkem.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2rzqwlyjl.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2pwivttfd.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2novbppnx.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2nduzoqqd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2mwxzdzbx.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2cpcxrqbj.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbrrpijq.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2alkjthwo.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2ooptehpq.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2wlstmpld.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2jijbnzeq.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2ldjgojvk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2eddtluzs.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gt2skybfkxt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2xbunzqtr.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2gianzgpz.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2whehfhub.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2ipuyviqw.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gt2hcfvaigt.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aojfhfvr.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2idtdowvc.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2sbarqxfx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2imvohkfc.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gt2wejfaoee.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2hvllouax.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2qjtiytwq.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ekeyynbi.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gt2elepyfkx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2ypzejils.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gt2yqvgrnso.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2rzogzxrf.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2shlceiph.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2ebqekuyd.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2lvlghnid.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gt2qtdieyox.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gt2wsoutnox.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2bzmchndh.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2dzrfycaz.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yapeznyt.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2zplpndfs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gt2giaspgnr.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gt2gipahbsx.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2gptvjlyp.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptmztfzv.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gt2xnfeserz.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2vomvzxfk.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2nchhzdyd.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gt2cfpfcxwe.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2soieopal.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gt2sbrldhmd.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gt2utisbbbw.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2uezfjnjk.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gt2hvhgvcoa.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjedyxef.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gt2cieqivbc.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2aqbatodo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2zistnwsa.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2hpsvdcof.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2yybwjhyf.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gt2sqsfeesn.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2tsajapfm.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2tczubrut.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyludopq.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2eimwmpud.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2eztkaqje.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gt2qxldshsg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gt2shslpgan.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gt2pfgkrebp.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gt2hxwxftwq.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gt2zptyufzi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gt2yqinrchh.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gt2ebsusmpv.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2pdsazfya.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gt2rlisvdmo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gt2vdjkutsa.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2uhpgnrwx.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2ezgvgmux.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2zuibrwsh.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gt2xrpczeph.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2evlifjor.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2fxyvxnlc.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2pfhljsue.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiqwgteb.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2thimccot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2bsgnupak.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhabjfam.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gt2vffehqlg.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2nxkilgyg.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2xqvqfqkd.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2nojkmvuo.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2slheiueh.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzmdnezt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2rvligual.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2jugedksa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gt2twskgxkk.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2ghwkebxx.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2vlwumcdz.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2gkzaqvat.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2gbkeciok.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2ynehhnrt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2ttavxrnf.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gt2gvmeqngz.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gt2qkxfclvk.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gt2wzedmdhg.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvwqgfgr.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2edgiomam.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2nswupyii.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gt2dgihiosx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2bmukydsy.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2tklrdkdm.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2brhswpok.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gt2etxpvvyq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gt2fdmjczqy.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gt2pyhcdovg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2eqvrlqst.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuzfcnzp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2hbiqyccv.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2tzfxkayy.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2ohaklksq.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gt2ivtnypjf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gt2iaxytbpn.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gt2uqnaeowv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2wejoobwx.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2qujfpizj.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gt2hyxxsebu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ttervwpw.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gt2htcslmzw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvzrtjdn.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2fmuozefv.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aiflxlwp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gt2kvzigrmt.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2nteuiipn.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2pesowuqx.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gt2clzzozss.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gt2iudpryuv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhjvnmr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mstfnbif.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scrapyza.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gt2dnpnanma.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2pcddrotf.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttjfsubu.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2kuiyhcmd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gt2atxmjbag.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2coxgrkhc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2rufuxqeq.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2prmmgznc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gt2flneghua.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gt2tfovlhoe.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gt2hqfszmie.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2btjnpeok.html


<!-- 参考信息 -->