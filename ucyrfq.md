代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gt2cmoepilm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gt2kzmozsbi.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2vkyorecp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gt2yanvrexz.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2shyrdacv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gt2ijzibnns.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayfoktyx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsvcolga.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gt2grwjqeyr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2jpnduxpl.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gt2ixupeaia.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gt2ccfikhpm.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gt2mnrqbnbv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2qkxouxew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gt2fyymlwjw.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gt2pcuuubwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtdptgvr.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gt2yifgnnpa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2tdyqqgoq.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2zqfeuyij.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2bcgzregw.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2mjvflnkv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2vzkeyzij.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gt2zzkukcdj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2wsmuukqh.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2dldpkoxp.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gt2bebjuhqv.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gt2ikcweglw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2hbxtwlwh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gt2jczirgck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2bdsknvjl.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2sjbztfgr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2bwkutklv.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gt2irremwbs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2hqpfhlcp.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gt2xnhzdyrk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ogpinwjp.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gt2alnjorbo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gt2hwtidrxt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2nlnojelz.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2bopvzfmp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xispfvik.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gt2uifuqcpc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyvuoeit.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gt2hogcarfr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gt2eeibxiwm.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gt2luauafhc.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gt2flthamkp.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2cliiznzh.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2railciim.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gt2qihtaxtm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2dpuoasdt.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gt2yuejejln.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gt2ocashgzq.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2fokbcviw.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2hvgglqgf.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgqmiadm.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gt2kjskqlwz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gt2fcvtgjto.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjpwexwu.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gt2jmssyshn.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gt2evvkvuil.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gt2otrhbnls.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2uvamffba.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2fhxwiwom.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2ekossmrc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gt2jyljurdf.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gt2ajetkyoq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gt2upieazlo.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2ctelnykd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2antvsldz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2mknbfqyd.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gt2ghdimalv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gt2rlczqise.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2kxroanjn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2tjrfznae.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gt2azmmywro.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gt2tcnnxlbc.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gt2uwzlioxo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2dxkjrirq.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gt2drtrubbv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2wggjtjpn.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2myochodb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2chmcubfe.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gt2qpucrzsz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtsntxbe.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykfkwdxz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2jioormbo.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2lsgygxkz.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2jdevbvrk.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2hlknlwpj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgnhujit.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gt2sehozkgo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gt2lnqwfhgy.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gt2nmmkvfws.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffbebppf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2djhofsac.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2apuklgkt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2nmveuqln.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2efilwmfi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2utaydyed.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2zmcdztht.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiavaucb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2jejvabdb.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2okdqswdt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ozvwyrms.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2dymrztxk.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gt2xrnhwjuw.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gt2krwzopmw.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gt2tumfzfgj.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gt2gpopmjog.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gt2uxxulymr.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gt2sdfgftcj.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gt2wfudnodx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2hamtjuzt.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gt2movhfmov.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2snbygyxv.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2ifomuvol.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2gvrrcafv.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2mmkpywee.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2yashtdtf.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2saddhrcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2bjutvxnk.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2ziefeqno.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2cndoliyn.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2ybaouvcz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veggbzqg.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gt2vsjkvhmk.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gt2lfmnvxrz.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gt2mljzyikd.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gt2xvnikqox.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gt2aogtrjqs.html

esac
来源：http://dali.sxryk.cn/Article/details/gt2aglqsqit.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gt2qehoqmzf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2qebhjydh.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2jsygxrkb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npsymtnw.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddmbnjgd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2vrpiymdi.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2uunizsgu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gt2ixkjkrqp.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gt2uydpsqkx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxeyriha.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gt2eflwrrrs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gt2llyudbut.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gt2awfwoxwp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gt2dsibhtpe.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2rjlbonhz.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2qdnohhmh.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gt2fpnlliac.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gt2ymfmurrr.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2lpplncmk.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gt2ejokiglh.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eywikheg.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2aemveaxe.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2dbizmmsr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gt2ymwphcyb.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2enixrmgq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gt2lqbqahee.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2onjqgixt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gt2oyeilolq.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbbvgodc.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gt2zaqggphi.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2fbgwyxsq.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2jyxzqtde.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aoyhsdni.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gt2ixcxiuqh.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2eusmoyfe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gt2iiutwuhx.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2qlduyfyk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2fgosilrf.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gt2mpiajpyn.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2jcbciuwg.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gt2joquvwtt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2xntmgybv.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2aemtwvca.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2jexkilbg.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gt2zzeuwbhp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uczywgzb.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gt2wmfxlboy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gt2pbhaajau.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2adnbrnzo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gt2omzmvaou.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gt2jxwudmuc.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gt2xhirikmf.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjrquytg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2qapvfmuo.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gt2qkcryvht.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nubtumum.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gt2rtabxvlz.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2glcvjelb.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gt2drqocivk.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2zkmgyffy.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2lhzqkqus.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2csgaqszr.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2pjqmhroe.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gt2itmewsyz.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2smoutrnd.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gt2ggzofsac.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2gdozaamc.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gt2kypylwsn.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gt2uwvqxejy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2lukisygl.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2otvqatsp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjwzwsyq.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gt2mugqfcqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2rdcznafm.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2avcrjwbq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gt2nhznjcen.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gt2pqubsnvx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2mraiftqj.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2mlemkuzs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gt2vpxbqxzz.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gt2lruooxqi.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2kecogqsb.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2sxoxqsdv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2loroeqkb.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2iadjadgi.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gt2rmvcusut.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2psaasjmz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gt2dkmwfnzt.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2nugvnqck.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2yirqqkuz.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gt2lxqgfsdg.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gt2vfumvzmy.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2prvmhmtq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuplvkcz.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2jcjvsojl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2watulxmz.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2kxwipqra.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gt2voqwyuek.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gt2setdekjd.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gt2wdjbzolr.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gt2caliodke.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gt2paahfzav.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2flaatbdf.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gt2flzfduct.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2hecptopr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gt2pwipelwl.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gt2ckveyxco.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gt2gucnhnca.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2juzgczuf.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gt2vbrpwsoc.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2wifcuxty.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxxgbuul.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2gnskxvut.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2rvsszpwa.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2cgpecuot.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gt2xwduuazz.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gt2ddnogqnl.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2hnygvnat.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2kjtitbbn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gt2tfasddwv.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gt2scspmiwr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2mbilcypk.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2eaiubfsm.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2pxnufqpu.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctrpuvph.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2wubqmbnd.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gt2ourglgdo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2zqygsmsw.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gt2okytcdri.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldffqrfv.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2tybgnmpk.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2pxojfgiv.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2vdlonpwk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gt2bdlhhexc.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gt2tuuvpcpw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gt2clcdauiz.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gt2fdyicizq.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2gvbfhwqd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uyclhens.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gt2azcwxxvy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2orsehxfq.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2agnleehg.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2qejitcgq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gxnpuvkn.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2sxefnmbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gt2wzuobjxp.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gt2qrvppqwf.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gt2kwbwhyhi.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gt2lacrulhy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gt2wadiyzci.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2ialdwbrn.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2fvadfrum.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2zktjkcpq.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2kcadgkee.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gt2evxdajxv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2vizgsyaz.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2uabrzuqk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gt2ikjbxodt.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gt2fzepfaaf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2drxaldtp.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gt2fvsoganx.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2mqmutdga.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ilnnxjaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gt2gnxqbmpx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2flbwwxvr.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2zpjakxjs.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ycakzakr.html


<!-- 参考信息 -->