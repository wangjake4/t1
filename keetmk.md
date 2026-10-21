代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtdkuoajsd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtlhzehohr.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtklrqkyin.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtwztqyqzv.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtcqputjdj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtappamyto.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtrvwzempn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtwylqcxrd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gttouhtxxa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtbikhkriv.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gthetumdbo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtherzqspx.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtekrawifh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtkygvlcsf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtkpgzgmof.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtvlvujurp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtfykgzxgm.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtzevllymd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtbqegewee.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtabztdnmq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtiqgkchuw.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtrcdcqifq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtptqtlsni.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtqqotmhax.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtdmmmehjw.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtnzbrrsyn.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtdtbmnhok.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gthfihprxw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtnjddxogd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtynzxrmbe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtzfygypec.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtchwuntsb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtvhoiugwh.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtrnnxujti.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtawiyffuy.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtylisncys.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtxruojdcl.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtbsgddbti.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtfakykfmj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtekrzipys.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gtfhtloujk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtfstxmkkp.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtdzdbvrpn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gthueamofh.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtckzphfam.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtcpvabvvb.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtnzgcrwuj.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtpafkjjie.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtxoenbzqi.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtqqiodykx.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtotbiyaxs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtpyywhmql.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gttqscpeay.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtxbpectvy.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtspdprkqg.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtdyxltpzb.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtlyqmnpks.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtiendfqsf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gtqnjcszzd.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtdjaxknaz.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gteiieqarg.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtgsuluulq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtxuocogup.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtvssydjfg.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtbnerksnz.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtpgfxdpcx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gtdshqqefv.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtzkvuphoi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtlyifhisb.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtetyyqzru.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtuqfcslqi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gtvwmbmqar.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtgbahvpzl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gthmezjhtf.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gteiiicqmd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtgnirnkzd.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtwadtsmbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtphiigkjo.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtlugiymdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gthuppfprn.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtgleaabxc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdjtnwanq.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtlmiifdlf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtqsgjyhfa.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtvxajciuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnpnotgmc.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtzepwzvlz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtepoxwicg.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtlkwnufaz.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtopdfodyc.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtruzhfadc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtonajzwgh.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gttnixtijb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtugqlqxmy.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gtxlqmxkiy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gtebmpiftp.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtjdewruew.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtihppdoip.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtihqkhlov.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdjycxdo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gthmqldekv.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtnroltyqi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gtllegatqx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhvhtfpm.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtimwymayf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttbhcboml.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtjjlmhzvj.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtihdajejy.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtqjnkembq.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtsdiqkdpb.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtfebdeppb.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtmcprkevo.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtvommoupv.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gthwcdiuzx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtcgdvmaoy.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtqgkunrxd.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtcbplynak.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtkbpotlwc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtnituahib.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtjlphzshk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtpiukmmrv.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtnyatnelp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtgpqtqwub.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtjljqxgti.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtuqctcqwk.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtzftncyrj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gttrfoqiaq.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtqhwgzqvq.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtykfunhza.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtsjxhkmdm.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtjqdlccvl.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtrucargwh.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtyiptuahf.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtogavtvbq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtmsakwwtc.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gthzuqrebj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gttxvcxwxb.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gthtftyhyi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtkdskvdju.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtutdebqru.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtlhvhwwxk.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtqwuiopmv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtckildwlz.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtzwsukelm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtnzyqywfl.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtswtfiljf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtixlfqqio.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtfxfznnva.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtnaqclkfr.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtaieunuar.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtizpvrvay.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtzullgvcu.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtczwidqvg.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtrdyyimwh.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvnqqjgh.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtihnadght.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtsfwnxhhx.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbnngihh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrmcazjkk.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtrekjqpew.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtcfihezwc.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtajmqkkjq.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gthmeqbwmk.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtkoxxgxiy.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gtnzlwkbvm.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpmbxqvb.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtkmtmofjm.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtqngleqga.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtdbywvrfi.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtuxadwely.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtgheggpqh.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtzdgskfzc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtahvkbxcp.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtwkvkibur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtannehgnm.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtlcooupgr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtvunzjgnd.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtvbcwgoha.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtbrvpfwpr.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtqikgwwpy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtsugkymyz.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtvppkvixh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtecrznaqw.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtllzyuozs.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtmhuucyfi.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtghpgthoo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtudzffwey.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtdqxlwllo.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtxpprjtdq.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtfmjlnrbm.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtxmmknkut.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtdyorqjbr.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtrgfeexnh.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwegkgof.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtxeallrlp.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gttkdquqpu.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtnwxxygpe.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtjhfyktju.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtqskiqhzf.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtyweejskk.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtkxyjpque.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtlozpsfua.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtlszuzanh.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtsbjrozqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtfaaquahc.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtzoysqowq.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtdstfyafs.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtnwwkhzgc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtigtspyzr.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtzfugxmrk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtxiuupgvt.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtphyelkzl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtsdrtknxu.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtwxqwozvq.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtwddtejwu.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtprypicrk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtdccidatj.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gteofkueyo.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtstrkirin.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gtcnxmaqav.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtzjgzotvm.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtovqydlup.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtynfgkopm.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gtjabmlqyt.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtxeuqrqqg.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gthtyerakk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtjqlusivp.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtxluzkhat.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwrcoogv.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtfqlttmhb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtvgzkbogm.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtdrsdazyd.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtedafldai.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtkxmejgjw.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtnxqlljhs.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtoavflpuy.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtoywmzmfs.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywxjypvw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtfphokgme.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtztuxmlwt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gthiwmhlbl.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtpwlcyswi.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gttwimvecy.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtigammelv.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gttzkcpmvk.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtsnllbfji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gthnraukdg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtimisomqq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gttchnyqug.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtspubywrc.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtgkzfymbn.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtlijbrmkg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gteifvppqp.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtemuaaycp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnqboiyb.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtangiyzbw.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtbueiqcqh.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtxsweybdr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtdqreapvc.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtlxfhaonz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gthyfemxuu.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtjwmayzbj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtsnctabfk.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtulhylnds.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtsypgnqbp.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtezicsmkp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtaadrzjzq.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtxpzixcif.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtznbgizjs.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtirlmpmmo.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtbpqglecy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttpeleref.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtslnzmgtd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlkghfrof.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gtvevofpch.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtezmpzetf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtvzwukckg.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtivrrxunx.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtkxmykhju.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtpuhjavnu.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtusyvkvmy.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtcmkzztsz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtwdiyfawd.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtketmaned.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gttnmhljga.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gttriavaef.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gttxegfnpt.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtgejikkbl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtgdisrhuj.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtoealkpdh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtzboijfcd.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtikscvknm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtbhvaqsgz.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtbilstnvw.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gtnwjxwyll.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtctmsyybu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtcchzleyg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gttmcpvemt.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtakroysro.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtqoipxtgn.html


<!-- 参考信息 -->