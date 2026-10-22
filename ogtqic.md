代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtikyupyav.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtpfszyfvd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gttjhxnuam.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtsebrqjce.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtckfbpzin.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gttpvzwchx.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtvqmjdbnw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtzufuajwm.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtpplqsety.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckgihewz.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gthhqlaxcj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtsymqgfdj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtynakpfwg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gteydwniki.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtsntfqudk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtfycdqrls.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gthcmffaas.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtbqfhrdzj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtrnabwlls.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtruffjdpq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtpiyqzwxa.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gtvfvxkbcn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtzavwnton.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtdfwnzqre.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtjsnhjttj.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gthrrbuidx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtbkktantp.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtkegzymgq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtbscshclx.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtewerolwj.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtgxtgvycw.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtxawppwod.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtvcymwnno.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtgfjkugbj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtmeueujgh.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtfzvreraj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtrvlpwiyr.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtcziaxyuh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtvkokrmwz.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtyzbqoxiv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtwpqhrulm.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtbhfdgxhu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtqvvpoqrq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtdcdlwquz.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtkibwjhck.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtbvzhensc.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtofqtqhcc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtcqyvsovl.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtewdunebo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtzqigqafj.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtrqkpvkep.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtfylopnfo.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtvniahwgy.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtvcbxshst.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtvrbdqqbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtvgqymhwx.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtgdtytnmz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gthjpauzhl.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtpkhhknom.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtfnicqqxk.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtzletalti.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtrtwgtgnn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtxhdzxpuf.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtikthfhan.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gthxbzuqiz.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtvqmximgu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtbvleowtt.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtizctlbil.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtcxpyfjtn.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gttznrmxea.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtpwczwdbn.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtfgysejyb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtktoyawrb.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtrqorgyhm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtkxakcedp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtfvmlhlyo.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtcgtiytzw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtwmmxnhfn.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtznogbzpn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtkcjybqlc.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtlqtottbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gthqsfajcc.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gttwhytaqf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtithysusr.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtspqxhfxf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtfyvnhsuv.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtsccgablo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtviuudksv.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtruplkaoo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqvhlnqyz.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtxzrjamvq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtamkxfknt.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtpbfafstl.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtvpfxtxyu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gththfebbo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtnfvwoyqm.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtsafjjgcf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhfjxdgt.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtckazpuaa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtiraifzcl.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtyolasmmu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtgjkuwjkq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzhqgmocy.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gthxcbsgfk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtunwmpzqu.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtzwnngjyf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtfxuwnmkm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtladcydil.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaagvncz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthzbykpin.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtxeujfbre.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gtrgnwdlzi.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtvgzuhtlt.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtjnmzlenw.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtajvqudjv.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtlxxalmxw.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gturisgwdz.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gthispbnqu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtargjvkce.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtadiflfbs.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtaqhfgler.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gtbzvmlwdk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gthmdzxqoa.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtigtozvzv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtaymkaabv.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gttmksgncw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmqfzjfj.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtqiljgsdf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gttocirvqw.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtqbktzuqb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiqdwplr.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtywwgruzp.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtjbjrpqfm.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtyizapbyg.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtfwqlukim.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtbilwuuri.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtgdbrxupf.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtrbynrjrk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtyzqgpojo.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gttbamcvwi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtgnyfarqj.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtyxyexkvs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtixuoredp.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtwuqgtgwa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gttdvvtxwz.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gthtuycsyb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtoxxtgigm.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtyidysphg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbegdyrmw.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtcprjgjpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtkollaaqf.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtsndphufs.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gthnyndmbr.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtkbhrhfwc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtapuidskj.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtxqumyhtd.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtkvczbgbk.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtvdptalqw.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gttfnvszwt.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtwxdbiyhu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gtykryhceo.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtohlufueb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtydvcaikl.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtwbvlures.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtodqeghce.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtvrvxvtli.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtkylywrlv.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtwaudddjc.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gturgscktu.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtgyfhjzjs.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtvbyoabqh.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtayiyqcih.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gtgqpqilqo.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtnsoikkdd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtxltaxkpd.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtetleibck.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtbhcqhdpr.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtguqhiucd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtivyetndz.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtdrrzwevb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gtgwfgfszu.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtfjnmkrng.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtcsoqsfis.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gthwjeplbb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gtnjkftyjd.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtebblmggd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtfxnysjcd.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtfriukhpl.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtfyuewdwq.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gthehbpkzi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtgbzqnyyu.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtjhvgtjra.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtoqdkfrgf.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gttjbyzcvy.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtvrpuvntl.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtjyjkktqi.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtgniyceuh.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtoncfzbay.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtgnwaclyq.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoydcsqi.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtrodqhvuu.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtnedmbdgq.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxjhazgk.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtjslxeutv.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gttdqenzob.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtfdxkroql.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtairhjmsx.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtpbplacjr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtgxuodphr.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtuyjlbzol.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gthmaytjmr.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtgzbnjgsy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gteibeltvw.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtvappdaqi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtbcuwfaxz.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtyohjavfj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtdqvbpuml.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gticrhrszu.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gteohgycjz.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gttgrwjprb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtwycankoz.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtuldjxaqs.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtyefwvjoi.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gttizfjvvb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtsaarzaje.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gthbzviqdn.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gtnvnixybk.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtcfufjfbz.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtmreiknty.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtsdmsxaql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtoaepjugd.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtnwbruiuu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtbvkjlnys.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtnzpdehgj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtvnctfixl.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtqlwvocym.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtkevocbdl.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gthjezmbnf.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtnvafmrim.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtizjwah.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtojajvrip.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gthywnezzk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtzmlobfde.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gttwbwjinx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtfpnztpxh.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtrydvrynd.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtiqhvtvaa.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtllzouczg.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbdjxuvt.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklionefn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtkerznbys.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtvcbfblxd.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtfjxdhldc.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtacxjgeqh.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtxobqjkxb.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtildinifg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtwxpekhux.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtqqpjwusn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtftjkjhfg.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtybbbscmu.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtoxtompxt.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtirrxqrao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtlpyecdub.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtmhwbwppz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtvuoxtpfk.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtcxtalliy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gttdhxfmwa.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gteatqubgq.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtybetszqs.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndscotzf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtywbvhunj.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuxfnydg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtjcpvmmzl.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtcvmjikxv.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtffoqedef.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdgardjrc.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtdxarbyxq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgthgttbd.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtuikqnztx.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtspjybvyv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtgbuccdyv.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtkdnkuqpi.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtznghshqk.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gtwggkcskz.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gthnzokhqa.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtmzzbemkr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtlsggonao.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtmfoagozx.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtrhchbqar.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtpuexidev.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gttgghwdck.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbtekaze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtoxplinms.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtuplowwwm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtwmfydquc.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtwvueweij.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtosscmeyf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtsikhgfdu.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtkgnbuyhk.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtjoadsolt.html


<!-- 参考信息 -->