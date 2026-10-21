代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtwpyxwfns.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtpauuoqmw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtvjkisjaw.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtuzffsqgr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtbkzhwllx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtquhofaau.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtmoiqqsci.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtjqyfkuac.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsntqxuxx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gthnmckaks.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtbfgaqhgr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gttjlakdhv.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtbbhsivcz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtmufezuwb.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtbaaolpsz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtizsngdzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtqtniywxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtgreewbcp.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gthobldueb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtzdvdqosc.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gthcyoxuvb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgabfllcj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gthevazkql.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtvrvdwzjf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtkxvujdfs.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtllbvaien.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtyajiywjs.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtssodbadc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtdkpgceal.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gteztxnlix.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtczabdxtd.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtnqhvnkgp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtzoosoenr.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gtfebzvyoj.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtqjutucno.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtjgjlkveq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtrettjuhy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtoskidknn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtrujltmqw.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtyeisxarm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfgyrtayt.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtxteljeyy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtdrowaulm.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtbowloncw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtjltohlmb.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtxcbpckrw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtvnsrkqaq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtwfzdpiom.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtrriuzlau.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gthzcklrzy.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtepbchcvp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfnjiasj.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gthgzblrvr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gthaseirrp.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtvqxxrhpr.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtwmgmhkvs.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtvxkbvaci.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtubxnfgsk.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtexaoqlxn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtleqdfhyg.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gtjcejibhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gttqbfkpjt.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtuqdsixyl.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtsyvvvpqd.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtbycnvlua.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtmeylzydx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtctwdxnyx.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtukbmrzmh.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtkjbyvnvx.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtyaanhfwv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtykerbqui.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtyetejlyv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrtghefrg.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtctjyeefp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtozoojlba.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfjczfmu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsfyjjzh.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtawuvcnge.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlvhkcrv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtzvrmchhw.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtdhehnoic.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gtghlnrzph.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gtxytwhant.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtclivzlps.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtfjjytjfm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtojgmckbp.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtvndwdbhd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtyskhggqw.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtdtvbwuld.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtstuobxek.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtbqbxyasw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtmcwqfupx.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtuwabowrf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgbjhlxqu.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtfdcsspjt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttlpcqohw.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtzfsotprm.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtdvvxmkow.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtietcinft.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtnogtdarp.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtihpgilfd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtvuoxbgmd.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtcpehxfxi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gthgpiujln.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtkrueboao.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtgxcghvmj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjjwwgrpe.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtoilkitfk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtwmjsyxgc.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtlvcituzv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtbrtemjmd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvmqjfhzl.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gtwfolumpx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtslevqzjl.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtvblytrcv.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtyeuxxsrk.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtincxvxrf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtrgxngrjb.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtplzibimb.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtbimoruzz.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtawquipby.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtjdihyipk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtzphoydnp.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtathdfxsi.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsrczpsci.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtqtiopxxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gteohrvkhn.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtycaumeal.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gttwjnazpb.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtzyehdfgx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtvvpkpuwy.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtxciulcta.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtorgjntzk.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtwlmammxu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtejsoxsza.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtfqefcsub.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtdqmdiorz.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtixlvdwmi.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtracpaqrp.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtjcccsljr.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtytqubjsh.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtrvpfjnjx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtwaabjjvo.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtvdurhvtd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtttiayscc.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtsjweuhvb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtijdpautp.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtarhcbdsw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtdvfchavn.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gtdkijboho.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtmddaxiiw.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtlqepywpg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtqhzmicwc.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtcpmznmml.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gthcfzxlic.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gthbvwikjn.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtwiuhunlf.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtxjhybqrz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtmkfjmord.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtiqxeywrh.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtzzylnmpe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtthbxydso.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcddxgxk.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtockdapcs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gtujqhlcxm.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtfetgxvxe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtlnvgdicr.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtpyrrgwmo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtegzawelz.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtczxkwyrc.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtfameghqh.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gttjpsdlyb.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtgtfudvob.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoyejkux.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtjwbbzica.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpdqyuub.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtnzztsmmo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtovqutboe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gtlaxwkxfj.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtucxrdfhy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtjbdyfsij.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtffhfmmhn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtibywnuis.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtbcmonwmu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtucfuhssy.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtfvrfutum.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtyffbbsua.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtmvfbbrsv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtxvacqrlw.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gthqsgydcz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtirgdbukt.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtzkdyxpkw.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtgoxxfujq.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gthbaylout.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtpvqmsokp.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtrkwshofp.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtejuqwwta.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtacxvfbuj.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtofduzvgs.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtoomsnktn.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtqwilwnpb.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuyzrcol.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtdoreiupw.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtiqzlgdou.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtxheceaqh.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtudiadlfe.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtkjkiyvyl.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gthetxaalo.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtjmcuywyn.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtpnljrhci.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtckiztbha.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtfclovwtm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmlawzoml.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtvuwrdbyw.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtxihpopce.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtsqzutuak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqmeclgf.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtqlimqvfa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtlnqxpcye.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtphkxwbaw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtxzcfqmwm.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtvgowhaqd.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtwexwybiy.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtnbwideux.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtfyumebje.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtinznrfuo.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtyjhlxzvd.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtugxgwsfu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gttqzcgdkx.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtoowwnotk.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtfmwwgyue.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtekziwfei.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtzgzqiqfq.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtxorbvjis.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gtdgsvvgav.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtcyhonmer.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtgcxqarpa.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtspynxwny.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gtqcdhkgux.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglmswgqs.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtziusecxg.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtlvtqrwek.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gthyhedqmz.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtxrclrhud.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtrrkunipl.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtgmrhszif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtprlhkunm.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtkbtgrfap.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtsheejiih.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtoncjxqrc.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtohbaqlsa.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtngcrfmzn.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtmpklawrj.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gtswmrlcgc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gthekorrbe.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtxfvpvrhi.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtohzjantf.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gtmcvbwlgw.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtjjxndfvq.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtntnnartd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtatkrxuhd.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtryygijzq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtmvnsawpb.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtgkqynoze.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtvnqkhzyd.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtrqsmixic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtumcvbaah.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtehkbfgmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gttdvmhxjl.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtgmqiqhag.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtcujkuydv.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtlpfpqhws.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtlgltynws.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtsuqtnhky.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtygksakis.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gtadsjnvbl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtyjyrznxs.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtztezswmn.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtzlvczacd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcgdemvlq.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtwgolfktk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbzgbdspa.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtfiqnlsvq.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtjxlcckmw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvvdvsuhq.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtnerxycxu.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gtadvlrjtv.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gtwvfobfng.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtwlpbgijj.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtjlxmtkka.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtzdlqcgwh.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtveqpzawq.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtovcpitgu.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtvxcdgubd.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gteuujirtr.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtpmikmirm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtiyjajnre.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtytccczqb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtfjcjmkeh.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtnrudngia.html


<!-- 参考信息 -->