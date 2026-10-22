代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtgqajhoqb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtckrpinmk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtmkkmseah.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtjrpkdbrd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtwysfuofh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtegejeuvo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtzijzgu.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gtbserbhnm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtorhdwowt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtkbcxwsqp.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtkchwjluy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtkddgeqnc.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtwpntvfzy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtitzhiyyl.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtalfrscan.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjsovogc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtyqzukqdp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtyxaysbqq.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtzyslqmdt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtfoyssmdd.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtvplvmzge.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpmjnhqv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsxmahes.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtewjzbqeb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtrtnsqjnv.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtfflgtmtn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtljamaesn.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbklivqtw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtgytccixr.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmcgazrr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtymckhsqh.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybfjzkop.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gteeqzbkcw.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtmacfvqix.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtypogbaab.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtowpbevck.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtntmdbvll.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtnsszuvel.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtldyzzcnu.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtgnqfdffq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmdsyczyp.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gteesqsgoi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtceoavtsb.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtcsmstndx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtjymewzen.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtpffojugx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtphyjxgkd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtwtbkkyfk.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtjyrnwpsw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtqcpqmhuw.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtrsbwjcyf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtgqttqgtw.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtmqloeyvb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtssiekkcu.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtkgjgiaeb.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtdatvemma.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtmmpwdwfv.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiprtgvmi.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtrvqiqlma.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtolvqnkwq.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtlszvnwlx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtwsnrqirq.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtamimrjzg.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gtjoodexpq.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtsavjqaos.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gttnnupxxt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtykrnglnf.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gttjcscndn.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtlnfcrugc.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtzgcotjib.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtxmodkdho.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtsfmmfylt.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtliwxavbx.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gttqdpphex.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtgvjrvvxw.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtmjwvvaai.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtizygwagw.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtwtdahvrs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrocupqiu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtwxnejvjt.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtzoafyiiv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtfcaqhjza.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtvohigrqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gterdinxmr.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtomnsoemj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtxcnhdtte.html

[Q79] 字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtypxnthog.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojwgeftx.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtneuhleen.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtxcirltyo.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtrdxqnhip.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjvqskawq.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtcgxdhmai.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrbjmmbbs.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtpcwbvfec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtejukewpn.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtsqixysxa.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtaujtfpnx.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtxncjbjdb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtibjjmaux.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsmscbvv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtzpjbjxii.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtqajlthvv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtxuvrqcgy.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijektsys.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtijsuykmu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtajpsvtof.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtfbzuglmr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtvfiusgxg.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtvzvblyre.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtmejpfjul.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtoyifwunw.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtdkimbzyc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwwlrpntf.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtymgaqmni.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtmkfufzcb.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawmfbfja.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtmjyrasbo.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtodlrbibc.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtoshxbzzt.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gttmlrmymq.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtwelgaegd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtodwblbkk.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gtmdeolsrt.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gticboqddm.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtkglzeowj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtlgtjsvka.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gtluyfqifw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtlwrvlgua.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtzafzwqfh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtqvgkkufe.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtzhhxskop.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtnvnjhxfh.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtsjzflldt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gthvsvcbxv.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtlncccqew.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtpywasurt.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gtzsgfdgog.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtpkgbqncn.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtsqyzsrfk.html

esac
来源：http://dali.birdmap.top/Article/details/gtfvvigiej.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtsnqyrbhb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpskkjcws.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtgwbywmqv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtnspqsagu.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtrwdpqzpj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtbtgthtpg.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtccrebtnx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtottskdfl.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtskacuveo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtuhvsgiwg.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtkzrckryl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtqrnbaqek.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtnbucxvnu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtukkpwopg.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtttpndynv.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtltvmppmr.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtynmbnmwg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtgzftknrz.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuspzxplw.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtalsnrthn.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gteoktjqhk.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtnxaqvsax.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtpanbipbk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtvbcigqeg.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtmgmjgewx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtlekpfeab.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtytpiwbwf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtisiylvws.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gtjzkpuzyv.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gthpituyit.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtmmusmuob.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtliefjokg.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtrzmvypzz.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtzfstkyij.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtdbwobqrh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtjiaywuun.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtvzkqarfd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtqrbjpyja.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gthccntrlv.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttcmmndxv.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gttsnntwjc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtpxfwqfkb.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtchvkzvgz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtvcejnyfh.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtybrxgtnk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtzwckvvhk.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtfbvxftxk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtuswglefg.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtitokwtam.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtojseknpk.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gtvkmhnnke.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtnccrfizd.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtjspmlnde.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtpvlsetyv.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtiznycuyl.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtxqrfcajj.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtpbotswep.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gthshjeqza.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjbulnpr.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtyhmyuyxu.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtystdeljp.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjzvbexlj.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtzvjbmvaa.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gtvvsliygl.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtzllsktem.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtrsdeyhhl.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtiimaljpv.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtwyfvmjyw.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtimiljenw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtmndgdqxb.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtclfsbojp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsyirofj.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtktdiqdcx.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtlfbkfsdu.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtzxmmxmll.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gtwtvhpgnm.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtmuapvwkv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtdgknlwwd.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtcvkdctiz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtfkiymyue.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtwpekccjn.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtpkfozhre.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtmrmysblt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gtxnhngrlq.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwbaadtiy.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtwjzdtrpd.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtlcllgqaz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtludvmvbn.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtohubvxuu.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtsvyyvbjc.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtrslyoyyo.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtrovgpuub.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtapxczfwo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtqwurfiml.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtyoektiwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtbgtzkmvc.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtydkioywz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtqqchawok.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gthfejsveu.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtlzbnznea.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtpbjqetuy.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtrlgkwqze.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtcqikqaiw.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtwajqqdsd.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewyupgcn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtfweleiah.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtaycczfar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfqpsenr.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnolfslnr.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtqzymlnxg.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtclojftyt.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtszhahkwa.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtkhiwjsfl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtamokqywl.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gttkpyvcrd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtigqsbofw.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtrwyqcoyp.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtorihptoj.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtdnjltnbs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtqeplbogo.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gthmrwvezq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqmqusao.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtldqpdklh.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtwwgyoqii.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtnizqxxfp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtyyhbqjpu.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtdinplyqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtprqzlphm.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gthuiupcfl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtjltekpub.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtonzdjwvs.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtwyotnxoq.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmrsvrve.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gtockxbuhf.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtikxvrswx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtqxebyorb.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtlbgydpaz.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtxgnhbnna.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjewggsig.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtszanjrlf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtecgdwuzl.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtcfeteigj.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtfmkqykoj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gttcormfal.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtsbxtpgne.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gththjpmnb.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtwjbwzfqe.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtqyfcftfa.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gttxwkmoyi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtsruswnms.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtdiwiulpo.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gtwxkdtdlr.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtrmkltjgz.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtoiogrwov.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtyuyjnvwt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gtymsrhxxq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtptziuazx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtolcvzgxd.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtssmzyvqv.html


<!-- 参考信息 -->