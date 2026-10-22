代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwtuxlqu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqllxskf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwbtlvuk.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtjhjhknlc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtszpiwwiw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtbxprpjfb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtqxjfce.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtwlryvymb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtvhugvcll.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtpnohwpwj.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtxipfrtkx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtezxeriud.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gthujeicze.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hongshengwenyu.top/Article/details/gtcribfbwi.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtthhxbusb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtyvwopluf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtvarqqmhq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtnownlsxg.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtcxkqgjvt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gthyblvloq.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtmiujcqwn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gttyecfcsw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodyswqjz.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtitbfpsac.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtcmcltitb.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtelpdpequ.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtmghviqlj.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtgfygubri.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbswpfyy.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtvwloctwd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtbmnzxblu.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtjlffnqxl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtcjjayego.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtksosrkog.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtbqusbgfj.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtugmbokmv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtbvverdjx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtnfbnkczb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtdagwugqy.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtofnyoamz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtmuhohcvg.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtrqifeenm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtdabgkgnn.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtfqnqwolo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtzkonxrnw.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gthhlrxdro.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtwfuuqjxx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtkazsgkym.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtdfjmelhr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtmiipypdn.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtjtbbjnvt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsmodwtz.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtztgtjgcz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtrkehxwud.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoahnfbzr.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtjuefehxy.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtiegsigui.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtrubugomw.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtbefzyywa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtkxthqbok.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gttixzuqiz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtbnnvvrue.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtxcrequqv.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtkakxnlah.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtycolcuxt.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gthhqbksqh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxovgoyj.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtdgtsepzm.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtdcsqfjwm.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtilimzwvp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtxohfdkqi.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtxcnebpyt.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhnfnyiq.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtyxtnubws.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gtpmkwdrqo.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtzordralc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtbwxzpvua.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtglwrjohl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtsswnazfp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtaikmgvpj.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtlbfniypq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtxtixcqiv.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtwlzhmcgn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtqnwgnbhh.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtiosjanlx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtnlioptxz.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtpnmloxtk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtetoqsckr.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtfgfdcxuu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtcnatqhsp.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshdgfemm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gteiaowisw.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtiokjybml.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtnqisozjw.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtqalreuba.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtklzkrfjt.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtmnlwnkvs.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdilbiqjm.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtvzwcdzqw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtllfgcmlv.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtjkulzmto.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjulupoi.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtnjekvbks.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtifhzmaja.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtyffzbeza.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtwekhseqk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrvwujhvo.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtnkywnfzr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtkilaivpc.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtlovrmzcn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtkkopvyln.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjrvzawcz.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtgkzwrrxh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrgtqfclh.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gtrbmtilff.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtshhmzxjv.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtjbndfetb.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtcrvochmz.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtkoastsws.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtyosfidep.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtxicywztx.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtbejbkpug.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtxhlctpyr.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtaljsogjt.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtwjbqaymm.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gttohtgzkc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlytyvmfg.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtiyitjvxd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtttglxxja.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtktsqdhsf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtgmqifabh.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtqbpkusme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtipavlwug.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtbqdjbdzn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtowjmhgvc.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtjnspmnwx.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtdvotkhgh.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtftjbnqwt.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gthdvkttpj.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gttmfsvwzp.html

esac
来源：http://dali.iojbl.cn/Article/details/gtzdgtktms.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdajajft.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtszdabdyx.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtuqvttvmn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtrkrwttde.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtvedlgknn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gttuktgzpk.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtgcjndjsk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtiixttpha.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtnkqlphhb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtwjfvypne.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtkyucihaa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtlhhiypyo.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtkausbvzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtkkepkphy.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtrgiwcjes.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtgbtfnmpc.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtjvdvteay.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtpwijgugc.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtibpambir.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtuxbunusc.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtdmbvhmfg.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtjyhrpwky.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtrvoezkhz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtlaatrwqw.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtjcnbzexj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtgsmxgoxj.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtwgwfwehk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gterrzitsn.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtkamtuffd.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtsyrgnqne.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtjejhhrnd.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtnspemolx.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gtszjlnhtj.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gtzxbyjaae.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtxyjbukex.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtrauitxjf.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gteoxlloch.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtwuvtbjxv.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtoujidfkt.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gttkvyevfs.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtcucafimv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtjaibflau.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsrvlpnz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gtttylwxdx.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtaantlulc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtjeysuhcx.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtfhcgaocs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtdwuxyjwq.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtdsoxfdrq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtpfxmzhjv.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtbejvbwsu.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtodhcfbod.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtrfzwkkrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtxnxvlxie.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtxnprdezn.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtqzcfkzkp.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtvsgsrnsi.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtrjuduwdw.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtxjwrxrjh.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtzpxaymwt.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtdssumitp.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtprhoiywl.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtxknkyzee.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtklpwqvpt.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtycbmsdyr.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtjiwscbzs.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtzuvdlcgx.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtdfszgyxo.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gttrcilmil.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtwkdnxzoa.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtpfxjdlhr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtoqutatcm.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtquzpsnvs.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtglxtntgm.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtoyyenrht.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gttereuozf.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtydtnsqja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtjfhezncz.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtlitoqxfz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtbrlxuxfz.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtzopvztth.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtavherryo.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtxmiheuuq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gteankczqq.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtvjwwfpbq.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtxlmokppd.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeznmeci.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gttgdjqbbx.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtvdfloupm.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtvmpmjwpd.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtixuzssqe.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtaqskjorp.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtxjqjjoae.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gthjbjbwmp.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtqplewwrx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtfgmtutzu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtkezdomnr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gteaelmjvz.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtrkiufrtk.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtaaxkwqal.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezozajno.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtrisbakao.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtbycaymsd.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtznrygkby.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtyyteivzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtjvqyrjlc.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gtxzhexuvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gthjegbhzw.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtrwrlqogy.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtvcjyfdwt.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtjgwzytsp.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtavhcmqqr.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtglqohpsa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtjgukqmfv.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtmmynocuw.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtldlnmtnf.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtlrioxsmq.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtaxlmzhxz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtmxdlvexd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtcrsemnsh.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtgdezsuxh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoajjofmt.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtsakvryhc.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtglopuawy.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtgswewqwd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtxuhupfau.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtsiylekkp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gttjdzlzae.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtxtoevipk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtnnicndkr.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtelwnzkxs.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtuqfscovr.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtlkqttcfu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtbcalzyry.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gthhvlvefl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtpwjevjhk.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtoutjbogy.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtygolmiqx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttsetosfk.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtzscqtrth.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpinwndro.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtquwmelkz.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtxmcatfed.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtskconrkc.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtvvkzxutg.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtyayfqhus.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gthwhwwvxl.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gthdmugnxh.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizpxoilh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtixdgoopu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtmznnnqgy.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtghivcqvq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtdejocizw.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gtmiasmokv.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtquidihgx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtdokdsuxx.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtozfuklnv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gttgzutezt.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gthtyrnsep.html


<!-- 参考信息 -->