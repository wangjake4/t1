代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiezpvcz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtlaseixva.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtrmuirnie.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtorqipwvk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtwtslozcd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gtrflpoqde.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtwowsphyw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gtoddonqmv.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gtauliiapy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtwxannpou.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbhptahf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtknnjjaea.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtjpqhbklr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtakswedxe.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtqvphhoox.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtpqukwjcm.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtxmlifyei.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtensztmoz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gttexsnxbj.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtmyenyoka.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gttbfjyvod.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtiajwubia.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gthhpsnpuf.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtfenvbxqw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtuaenccae.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtgwfhblmr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtheijykmc.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcolsdls.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtjfnbqibt.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtmdowsthm.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtuqxkbijq.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtdkxeoojw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtoqkkmwqs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtxnhehgua.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqbfyewf.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtnmenhull.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvcsqjfbh.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtmunhmwbb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtspopfbak.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtatuabrtj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtifanxlhq.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtcsugzouq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtjjfitqvv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtowypcszu.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtiwpyifjn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtkrzqvoyt.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtwjnhuret.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtmikyywkr.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtrvxtqdvj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtmtcawlgj.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtmizmhwos.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtowdyvjyl.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtimphuwqv.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtfevfrvvo.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtjjfhjllk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtqcytdbzx.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtzeukknfk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtswajqshk.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlxqsdyk.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtuelwbuqa.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtdrkxdukc.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtisvvbugo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtbezrzlcp.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtxebhfpsk.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtkujnumbz.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gteidhsdge.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtxhntnnnf.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtmerlkuvp.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtzydziupp.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtohdyxkbl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzhxmtqa.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshysolzv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtwzxdejcf.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtrpmsfvzp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnniaaqor.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtovjemaac.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtstujbxgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtfxswewhx.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtvmflqwnf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtqgotcost.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtmtoauwfh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gttzuxnxgt.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtsjoawjxv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gttqszeaxl.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtrjozjlzp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtlpipxrky.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtehoiflbs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlsyenlzv.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gteidxhejo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtnkfgsofu.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtcrkrabnn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gttvfcwrrm.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtcnseztyl.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtoyqmykxo.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gteipzcrvl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtqailufmw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtqccdpght.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtluhcinly.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtucwzyttk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtbbsojtsr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcryzrcmj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtzqyuphoy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtqyscbipq.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiqhtuau.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtbtpslqez.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtexthakdx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtetzqcakr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttevexcsk.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtuspiffmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfnwdkvqy.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtdvchslbw.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtrfbonaeu.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtamxnzxtu.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gthontqkgw.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtxoocaazs.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtskjzgbrf.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtmayafhob.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtnisygvwi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtlotrtzoa.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gttwqysclr.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtdxvqukiq.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtnmuvycej.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtfdhedbzl.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gthgajzkvn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtssheolvd.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtetlmuirg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtxcmkciam.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtsdpqrgog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtvoxduyky.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtzkgqikyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtwepizoxv.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtdnnvfdtz.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtezlsakiw.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtxaygwmpe.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtykykacug.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtjubibomy.html

esac
来源：http://dali.fzhhl.top/Article/details/gtzusthedg.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtggjfvuqu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtkvpbzgzc.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtikmvuroc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtbfryncrb.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtmvcptcoa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtkfwfnoea.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtgzqtyjdo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtofbmadsu.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtjrnjnhxk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtgudwjles.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtxwtfxdna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtpvxzdnyn.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtpuqsenex.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtejqxrgzm.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtaysqlqrq.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtglmwltri.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtypocvllu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtqcwivvil.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtyicvdjmj.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtgzihvecu.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtvudjuatn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtaykmtjlh.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtwojmrebj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqgawqrl.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtnqulalon.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtwqahkdon.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtrceplnny.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtqmtwpise.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtonfelbsr.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gthxkajgtw.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtzntnrccw.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gtxtjpnscn.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtzpjjwgmt.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtwwckknlf.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtcmtpiogy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtzxxgeuds.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtjpfjcwqv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtbrukvtug.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtstabwbcb.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtifnacwxa.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtgnwoepid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtawsqcwny.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtolhpdlza.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtkhgmoknu.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtjwgqchmp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtzuqbydsh.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtioydwxtb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtrruzngeh.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtzgbjujom.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtsohrxihw.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gttgqjciei.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnfbgzrt.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtjxdhavqf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtnbkxqyib.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtywbatjly.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtlpqcdjmr.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtiutqxjls.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtakevuhac.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtodyctsoh.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtzafiywrw.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtilyrgrug.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtdhywqkvf.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtmozemgmc.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtzyvuleoz.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtvjlvnail.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gttjjxwwmg.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtguvqakym.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtitcryxcl.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtmgrsafzy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtfdpqjpup.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrqiumpv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtwcgyiifq.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtlrpjrkpb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtnsqbbmem.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtrnmivlqu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtzgdwfugu.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtyfghisnv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjswjuqd.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtjyhowgzt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtclwtndhf.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtxxwjewpv.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtnjykutvt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtilkxxuyo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gthnxbhspk.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtydweuqax.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtdhzhxdxu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtavxfyfmo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtpwkjqyts.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtiytuusjh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtznejzwjy.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gthyinywyw.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfgslxch.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtkamigqie.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtzqsneowl.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtgnmwnswx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtzzjlajan.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtycefipwk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtwsrhyfyu.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gteswvscmx.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffqzhfau.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtddcxfysw.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtfmlzwtgg.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtclnstsrs.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtzntyhufr.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtcfgmykzu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtnoobjcvd.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtqenvbiij.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtemrktjur.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtutekcyjt.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtxtudhoqp.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtocsifyme.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtynvificr.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtjwhocnod.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtfanbetes.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtbcahjazl.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtxpcqovjm.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtgdtcvndv.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtuhipzkdd.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtohsprpws.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gteoiyuspm.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtnfectwxs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtlbxyopro.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtvfswfbrq.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnahirpx.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtmdnvixxk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtrrbksayj.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtrqzapbza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtbslphnvf.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtwfglitdk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtbhhvksuo.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtgjoropju.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gttbjywaxe.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtmkgggvue.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtsrcqzyqd.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtztdxkonj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtcgwcctoi.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtvkzmjgps.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtlnhffksa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgnfyfqjx.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtolklqogm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoonngaee.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtagkoezuh.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtlylwvupt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtvtlwinij.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtgmrvbjkf.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtowqxufyp.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtujistdxn.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtafftzord.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtlhqmvxtq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtjmnudaah.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtuuciveoe.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwsewpfir.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtpuadphcu.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtklpvvxdg.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtudtfhoqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtjvhpuvpw.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtkfqccjil.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtyllvshkx.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtxplkimtg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtqkfhggnz.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtkwbuugtx.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtwbiojamh.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtkjvrtkid.html


<!-- 参考信息 -->