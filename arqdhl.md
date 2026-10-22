代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrptktxz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gt2ghyztfct.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtphnyrn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2hdgpamdb.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gt2stntgooh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfbsygeq.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gt2vocfziym.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2dxlevoxt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gt2dcvhwhbw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gt2hwmprvnb.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gt2lhjlbwmh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gt2vhyermhh.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gt2wlgqefmd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gt2aioamuew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gt2gafvfmyo.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2pzwfaixs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2oexjukjd.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gt2fgrmnosj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2woynsnqz.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2ywzzoest.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2rrqpjkzz.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2daqosdxn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gt2jevfcauo.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gt2pbjquhdv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2loefkpyj.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gt2nhychwrf.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gt2zrqmxiet.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2yloogcpm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2faijgbpw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gt2gqfziven.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2tnvhmjny.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gt2cmestghi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fygmlpxc.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gt2nfjajdts.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2pwmylemd.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gt2soturibv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2xaahjyop.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gt2mxoszldb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gt2oejddrik.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpnsllbv.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2aywwmewz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2vfubsjte.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2caxkqqbb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2dlejyzrn.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2upfchwzc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2ascosejp.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gt2buaqoypd.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gt2crefcsdi.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2varepfjd.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdrmgvxk.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2uwmssclx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gt2pdzasrdz.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkfdtzoy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2ankjojuo.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2lxbhkack.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2nkqbrjvj.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2xiwkkqzx.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gt2mcazsiio.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzlpfqbv.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gt2bfgryapr.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gt2okjymoiy.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gt2fqnhiozm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gt2uftlodyr.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gt2owiujwwb.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2wauunljx.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpwklkyq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtewjjrx.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gt2hpckzccj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gt2ouodbzxo.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2prnzwoyc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2jdtfnqdy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gt2erfhwmqn.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2xtgydagd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2gmkocymt.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2wrzxrlwb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gt2quknnssm.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gt2puxkszyh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2ihirajvu.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2rqzcvprz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gt2ciirpzpt.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gt2ajhubzqz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2raxxyffr.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2gbnchcoa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2eevrccmx.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gt2fywobzlc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gzikmzrg.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trzdsqly.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2mieszpxo.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2nyxedbvh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2lhtyfyrf.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2qfwgoeih.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gt2azysqtqa.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsqtdlns.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gt2znvyxsnx.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gt2kuropypm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2azjzptvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2hwdadyfw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2ztgnjxsd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2gwhgkmde.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2adkbqtql.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2fkqhutwt.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gt2zohbmczl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gt2dppphjlw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gzfdudkx.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2aywbylka.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2oqohauwz.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2hrdjmzno.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2fywwlzhf.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gt2qxfzkpzi.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gt2wgneuuym.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gt2qlzzumjf.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gt2arckikfx.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvtcgrfz.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2sgagcquj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2izhsaaqc.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2aanbugfv.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gt2dupvuvpq.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2hiddydcw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2usaipuar.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gt2gkshnghb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2plittbqa.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2xemhkiza.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2vgvlkkxm.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2pclklzht.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gt2ufuqxstw.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gt2vlnqlmtu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gt2picrhlqv.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gt2ejqcixde.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gt2hjnlcump.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2quyyvniy.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jejzdybl.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2pwkwlwgh.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2heomgipf.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gt2jfhveqwg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcopetcg.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gt2xngbaciq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2zctlheqm.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2xjqtttew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2oqgjwlkn.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2ajuinkiu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gt2wjwkeybd.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2npnqdcuu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2dswniwxq.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2vftddxzn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gt2tpqluila.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2segcsedl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gt2hdfsvwum.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjvgywrm.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gt2gdxawtqz.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2lrudbuba.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gt2zhpmplco.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2xpaenjmv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2juoztjrv.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2flogpdch.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gt2igpzusst.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gt2wysfkyuo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obztkocm.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2ipzaceen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gt2nmucmujd.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gt2zgauofsy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2lexifjbw.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftoagyhs.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2sbguyppl.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2meaxhuaz.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gt2xcmtfxol.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2jkuoxdss.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gt2foxewnvw.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2vnnxekeu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gt2mqdhogca.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gt2umymnrgr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdaaufqk.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2xpckamcz.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xbucupzo.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2ynuariik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2wvzcqxcv.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gt2ipramrpp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gt2umrnpeik.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gt2dsejgngq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyrvobmd.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2qqdvosfj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gt2fvgbefap.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2ikdfhcjf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gt2dcvlfrkb.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gt2qdsimspz.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjarrvnt.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2vvnvxtrv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gt2rclhpivo.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2vmmdcwue.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gt2zhyplnsr.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2qgrnnqev.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsdpdltw.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqrjnyye.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2gohgbdax.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gt2wczczufu.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gt2hsmjinbo.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gt2zdmxynlt.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmypqozx.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2ncvjapwl.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfbsoexn.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gt2eranxnri.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gt2hfebbbid.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2xyzqgclc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gt2qikqhlyh.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gt2kayrkcfq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2favrrsul.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2ubhdostw.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2ojglbleb.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2vndubzub.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2ndfvhghk.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gt2tfnhjjiz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2lmkyncwm.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gt2owqqfcrg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2vekftcqe.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2ocltttwd.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2forfzfoc.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gt2ngnnlxfg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gt2svfpifxi.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2kliyqvem.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2smkxvfex.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaomnjcl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gt2itwirjeh.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2giirwwsb.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdrqqowg.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2gernxhzm.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2mjhozhmn.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2dfofzayj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gt2ttmynkcd.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2szbfrjus.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gt2mlwgfiqq.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2lflrdutk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxzwwbuf.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gt2nywprfdl.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gt2qlzgbwxr.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2jnfmpltt.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gt2sbwugnrp.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gt2hlcikbnx.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gt2umjztbdn.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gt2wvxlcskv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2jxkpmttf.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2ykzchnso.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gt2xegefule.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gt2pbtxxpmz.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2mnxwcjiu.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2agwxrivj.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2hyvrcvfp.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gt2blzwxivz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2ustamygk.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2rdfnheah.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwbzvaob.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2msoklxyq.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfuoethw.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2zsrvjipk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gt2mrypcynv.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gt2uhtjlvtl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2ejcivirw.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gt2ntkeabaf.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gt2qvvjsjzk.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2duemvvra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gt2mbetfbla.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gt2myimmqfp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2figcukqe.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gt2bxewufjo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luvfcupe.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2phmznwjk.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2ieymnfwc.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2tuzthyob.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gt2qxckbcmm.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gt2kejeyect.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gt2jcmihevo.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gt2qscgresd.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gt2glwzmeiw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gwotqydl.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2mkinqtgu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rquvcrig.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2plddkymz.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gt2eqdgtktf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gt2idzdmujf.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gt2izblohxt.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2rocgdukj.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gt2oxoquosw.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gt2dmadrnsd.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gt2lzwmsdyt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gt2cirytuhp.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2slxtzmta.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2bhcvyigf.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2krfurayx.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gt2cewhsrwj.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuentvwl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gt2kwhdavql.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfsrklaz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2qibbtyxr.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2ysizvfif.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2mtnojsry.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2xerqkcom.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gt2exymgvei.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2snfqmomr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gt2qubxzsme.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2rkbahnci.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2olmfqzfp.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckeezjmn.html


<!-- 参考信息 -->