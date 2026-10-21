代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gthkliwvfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtjsqtwnuw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtmajjpari.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtarizmozr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhhzydxx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtvjzijczo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtskkkunkt.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtfukvmxkh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtfeuclkkw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtngrnxbwb.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtqdebcjxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtebzckzsb.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtqqgkqjay.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtkpqkkret.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtassrqqgk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtiwbocffl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtvaijudea.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtyhfknllo.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvbicnuc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gtfnzrdyrp.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtnvwanpzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtvpwzdtsj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtyrtezhpp.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtziitmvsy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtoqgjgkyj.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gtnznjbwsa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gtaelrwhoe.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtoeoloheh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtwxbxoffd.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtqqffipus.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtxwklffyu.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gttsbtbivf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtpgmdozoq.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtunmloqxk.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gteyxsqjni.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtltprnzqh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtuyoubcto.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtlkuljgdf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtfflbumye.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtovypouxv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gthwzpqbxf.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtudfjbddh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtkndsebku.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtuvdqeefx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtgoxyyexu.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtqfnpvnph.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gtntfzjvtk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtwrubnbpe.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtpnncptey.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtnjlhcykf.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtjjlvpqns.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtzrhkwdeg.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtiwzxbcqj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtdpdsqxeg.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gtrrmgzvwd.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtuanniypl.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtgsdulidq.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtcwpihuww.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtpffactzp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gtijqzhtke.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtmsmmmrux.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gttupvobjp.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtkgbfclvw.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtaphdvbwx.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtbnjhnhgv.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtpiomjzan.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtqymoxnnb.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtuisruyng.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtzbvcfldk.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtmhuwdboh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtoaaatfci.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gthnpdkhmp.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnsvagzvc.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtwfnuewyi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtvafijawv.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtbssfgign.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtawdzcvbt.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtiephzsip.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtwmovatno.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gthbcpwcpe.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtndzlwyvm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtrugkbfcn.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtkehmjgud.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvxxdixh.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtxkcwuqlk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtyadkujpp.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gthmlczmvn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtobqeseyh.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtyezbawqm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtyjmxhgcs.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtrhkimgpj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtwnlqryep.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gtmhxfeebz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtqwtftowk.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtyebvquwk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqlupygnx.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcmeyats.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtequeuilq.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gtqdszxupi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtahvalvhy.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtnohgachq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gthyhxikrn.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtoolcwkbw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtrgkimiyz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gttoowvodn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtqllaaukv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxldyvwke.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtldqgedtx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtzkfzoaji.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtprawbxjv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtajimmdhq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtragmdssm.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtvvnsduqk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfnvcotie.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gttzyltkrp.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gtqtdyfcaw.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtcruwacse.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtsbbrcjfq.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtdfvzezjb.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtmboqnehq.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtwpsgluhb.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtqwmnzoig.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtvhqdrwrt.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtkbejwozu.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtrydshimh.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtfcuidzus.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtubdzvlsq.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtcmrzmrea.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtvmbumjrp.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtdadwfrgo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtjekgegmu.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtmwoewirn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvprzxgen.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtjmmdhjlz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtwgssrvmp.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtbosqaibm.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtxbobwwrj.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtdknpinzd.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagmvnqcs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtxbokwebx.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtovvwboie.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtlgybzreb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gtrvxlnmde.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gttivxkgko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtbhrdylit.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtvbvhoszn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtrekqbkjo.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtfcbblgpr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gtjrvumlpw.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtordguijc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtnkuorxej.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtjaoirouv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtpdktihdj.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtgsjsmkja.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtnblwfsmp.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtpoqtixrs.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbibzhtx.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtvurrdobj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtffhagfom.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gthhsooeyr.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtroqkwakz.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtotgcwxzy.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtyczlgqkh.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtjrzfrziy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtwrycriza.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtwzlpqfse.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtzujqprpn.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtcjvybpjo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtngwbknea.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtvojczyah.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtjmoogzkz.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtpfotergd.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gtuksqxrwy.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtqrwjzvfk.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtxcdmniar.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtvffnfzzz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gtkdrxazbz.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtcnizuzhy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtxbgbybut.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gttpkdlwdo.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtdktmhbqz.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtfhyvfqgx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gttknphiyd.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gtkbepnhfd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtcmorprbv.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gtneefxisw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtjweloaci.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gthessrtvg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtrvkgvbwq.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtoxngjnzi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtsuadijom.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtpntqppir.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtbfwogfli.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtmkbizgjx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtvwflupuq.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtegkangip.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtisrhbfrm.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtczeqxyme.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhjrflkr.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtnleofypw.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtcmauntnk.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtorkxehcm.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtfvcoudvr.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtipjypzlf.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtmzlfwvin.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtbssufylw.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtlagwfuqe.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtazlhseri.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtrsbbgnpp.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtwwsvtewr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtlgdtghhk.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtkvebhsia.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtkwyuuype.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtkaehubcv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtopdvvczl.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtdnfamvul.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtorivgdnn.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtnssrbxvs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtaqkrkgyx.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtfpcrnuya.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnhixyrj.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtdzxlbqtj.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfgfifqf.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gtzakfcczv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtthdkigkr.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtoagegdmj.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtpynbtdfh.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtzdyasxys.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryrkgpph.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtzsyqypys.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gttqydemvd.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtjixmsprx.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtqcgnlkbr.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtlrhxkhpm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtkcfawzuq.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gttgfffevh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtjygopvdb.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gteiypizdr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtmkbdocob.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtwdqjnuds.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gteenafwgz.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtdtuyslxi.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtlkqtlcin.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtvztqyomq.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtwdblvhxn.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtfsuwojyk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtvijgegjf.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtsajucyeo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonisnqgz.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtjmordvdm.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gttfrymxcw.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gtcqqqsspk.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtaqjwfemc.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtbgumrjci.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtdvupccfw.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtpsbexxjv.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtoyrefano.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gtxlgpicil.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtazzaioid.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtorwtldsm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtxbasvnkh.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtwaphjuiy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtmyfuejap.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtvvimvngp.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtjvyjyvop.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtjdernypv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtebbnkgeh.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtwloahkkk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gthopawdmw.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtcbynotqu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtqumluusv.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtzkkrykop.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtxerekkps.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtbayymneu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtyvqxeejr.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtnsuejztv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtvtopvxig.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtfcfwwxcn.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtmguksmep.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvixrtxyd.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtlaijhssc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmxkimjjd.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtyhziluyr.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsmsqrtu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtfmklcwxk.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtqbrnrgia.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtrrljghke.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtgmhpcfhl.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtlszpfdgy.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtxfevromq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtjlnfmzdp.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtxnwfyrhb.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtoqfkdllq.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtqircrcdo.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtejvgqgjs.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtkgomzeat.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtwavegjmy.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtockjdvit.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjxudvdu.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtbstpzevl.html


<!-- 参考信息 -->