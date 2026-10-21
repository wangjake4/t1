代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gtbqtixrsm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtvwohftfs.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtprfzhtqy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnllkikir.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtjzidqwoj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtlmuiwfdy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gtaovgouww.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtixlulexx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtxbrslpll.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gtvktsgwvr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtmjkhmzcu.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gtpcgozmzu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtytdbxbtz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtgusaiygk.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtmomqfahj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gthvfjbbnm.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtojrqexgk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiwpbwtd.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtnxmtwpzy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtppheetqs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqemkykfa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtkbwjwwrv.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtvuvgsool.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtqetqzrlu.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gtacgumfqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtghuyjapk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtedlodnqs.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtuzvdwrey.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtwlgeaver.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtinvqcome.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtahuwzqbw.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtsbwtnwoz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtftsdqazp.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gtspneivgw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtymmufrqd.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtbafrnfhi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gtbpikoldy.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtybeqyjpc.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtbcaeduqc.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtiugnumyc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gtehegkmmg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gthejmjhee.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtlbthheie.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrqrldor.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmnwxqhtv.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtdooztycy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtbvknfreo.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtshfhdora.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtigysrvrz.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtopftpmnt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtgoakqqji.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtwwsndbcz.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtnvxglxuf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtzkhpdvie.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtcitlqfdj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtlbrbccjw.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtftkumgpy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtjisusznn.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtorkmjexo.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gtxlgoacop.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwongfqbr.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtorhqzbeg.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtpnlotwjq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gtouyejiuw.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtrdugycog.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gtqcadcokb.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtrnfuvglm.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gttrpwouiw.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtzwroydng.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtjsvidrjc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtuyzxzupn.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwsuzefz.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtptudqwzn.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtrffvzyrv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtsbijynjk.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtvriffqgh.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtfwsjebsp.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtykyragjz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtiqcwwebt.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtwklrotvi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtgpeopuca.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtocohcabg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlagpbgpq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtdywqrpcp.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtsswshlhj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gtsueyelxe.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtwbzyatld.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtgimjkzzd.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtxutoatjh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtxozefqwb.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtrjxkxbdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gttfppnqcw.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gteibqixhh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtosrnreom.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtuxfimllp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtvxegfqip.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtinoielnx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtzogprpnj.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtckwgghbw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnzrjkdqa.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtcicxjtrh.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtnqvyvktn.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtbwrtykkn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtwobrsgaw.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gthmdcgobm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtkvkajauu.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtjxzhdlen.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtnbtskbse.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtptoizokc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtmihewmye.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtksfepapz.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtzrnxdjgh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtbgrxoqqt.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtwmyyngdl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gthzckafaj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkapzebsv.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtbaskkixm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuzjdwswt.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtqnjfafgz.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtomcedfpn.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtkpwxowkk.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtqawwycsi.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtdfvkdjxs.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtfwkppnge.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtmbeabewn.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtbtjbfooy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtpapewmkf.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtgtqumfme.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtamxcqevh.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gthzrmwxik.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gthxsutmao.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtjyqoelos.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtsdcnnquw.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtmgyxyxqq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtxzlyjlrq.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtzfdxqftk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtdkvoipal.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gtqnqdnnkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtxxjfzfna.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtferkaujg.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gteqpppvhd.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtgypzipgh.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtygbtmpry.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtbbmmajxt.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtbdkamwbr.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtfztmnlwf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtdezmipjz.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtcxsdvtbu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtfasmyukc.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtvzhkpdxt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtermvewln.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtvhggxhia.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtmdeldvni.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtonrhflqk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtwprdzmsk.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtlujbqjsh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtmodgjeqk.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gtdvwayeha.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtglndgxms.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtybngiroc.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpskgvtky.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtulyzufzx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gteufqgjfd.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtlwafsdms.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbfvdqvka.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtuvcxwfpn.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtqwwxcqze.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtpzxatwuf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gtabflypnn.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtukqlvfkl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtqycqxywp.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtqtajfmas.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbreafsjw.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gtqpbxqkgr.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtlcrdvjry.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtudcnwlau.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtywbxpwtb.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gtubgddtap.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtktjnghwl.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiinboac.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtbotpsuid.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtuhmteayk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gtvvyjmkrb.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtxgpwyhuv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbimtszj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtoymnssif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtccgxmsqs.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gtfhtevvjh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtocrrnxgl.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gthunpvhhr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtyoikqpgv.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtszxnsijw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gtvfyvtkpq.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtxojkzath.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtnoohtmus.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtjnkobcvw.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtmocgppif.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtoemswnbz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtnncqsjxl.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtqaaazdci.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtadvpuqfp.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtcvzvsffq.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtbxmzzrbf.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksfpctlx.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtwbivofla.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtxohemzzv.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtqxtaehnp.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtwfgytbhc.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtonjvekes.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtcqwegqku.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtofllcvtj.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtefbwaxaw.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gteqiabgfu.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtqafutrvc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtyhogylhs.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtwvlivslx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtcbktfllj.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtdkusvxyb.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtvywjwgae.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtlwrtrqev.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtaagigooy.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtazrghjrs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtitzfvtqs.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtbjbybxli.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtgziqmmgt.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtprfgrwow.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtkvbkyfgf.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gttifxysrh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtjbihhslp.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtgobtswbt.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgokeruu.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtdglcekag.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtkydpawxk.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtcakrlowx.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtufqrdxju.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtucwfquvg.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylaaqyha.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtounsasqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtdieemjzs.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtnoraxfog.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtsnkymtfz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtaogxxuaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtgxxytycl.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtraftxtsk.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtexpicoaz.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtudiditgh.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtswsugvag.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gtkrgjtief.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gtjdilnjfv.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtunjaynzi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtcdgluubo.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtvdqbddtq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtlhjlmfaq.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtnupikixu.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gtxenxkqih.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtnnuvjgoe.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtammibpfd.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gtvwaolubd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtruywgilm.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtnpcaoioe.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtmqohvlcn.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtnmsssrkv.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtvokfmtnz.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtdxtedekl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gtqglpsrzb.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gteaqqdudi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtwrgfkqne.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtzysszkrf.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtjaittybt.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gtbpsgaoum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtsktksmbq.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtdvkwyeng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtnwjcmuch.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtagrgnqmv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtwxtyjwst.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtiqjdjrvg.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtcenkltgv.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gttrqptzoe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gttdqsqdnh.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtsbmlttmu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtluyuolff.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtzhpbjidy.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtxtlrgbsw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpihbqspe.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtqepqknzd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpjlllafo.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtikrsxyor.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtqbrtqmsr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtrvzdstus.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gttihcljry.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtypbsmmjd.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtwnbzeful.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtwberyjba.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtlwqbbrxp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtlsqfbzzr.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtsmprslsh.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypzptofn.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtehbqjpwk.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtexboroas.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxgurnyg.html


<!-- 参考信息 -->