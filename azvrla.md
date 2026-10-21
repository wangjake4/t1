代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtmxwwcewr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtwxwzbxwp.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtkvpmedhi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtfjkszuxc.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtjmpkvvsi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtgiwmddsi.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtjdfqjhfm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtuzenrilr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtjjwjluto.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtfrxadlxr.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtdxluyxnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtatiehbpx.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtbzldnudi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtvyddywsu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtqlddvlyh.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtugljbxkl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gthcmnrlnc.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtirjoknse.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtzkutmbmq.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtvyyfmpwf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtuiukzrct.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtpjgacnke.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtocvbhowp.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtoxiccbkq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiismyztd.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtlnmspfmi.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gttgavqmdj.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtkzgzfvxt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtmwelqsee.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gttpjobqgg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtkjenzfrk.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtloytlqcp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpkvppxvt.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gtcllbsmxa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtdbtzpjgm.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtbzziepbf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtciflmbrs.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtagacdtso.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtxcwbzlsd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtcmpbyqru.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtduwmhsyv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtyoojhaza.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtawdeleys.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtnqnfjz.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtzsdmcdyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtorttkpmj.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtwagcaqma.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtrctognjr.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtepfacjwr.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtfzbwtdjr.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtzlqolzql.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtzcxgheic.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtbpmaklks.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gterxxewfg.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gtgmnhurxd.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrewerwq.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcajrxjlx.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtdngtpnsj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gtsfoyvtse.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtlkwyouiq.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gthjohnezd.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gthotrvsyb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtizozxmpo.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtabcyjqlp.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtpltwkzvr.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gthapoviuu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtlzxzjqbp.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtqkkuyqbb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtwqmjolev.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtwxfllsld.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtxabivgtd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gthdftjkzk.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtmtrnbfbv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtqnejcyaa.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gthqfnnkcr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtvbeveofr.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtqkbtyqko.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtjtodcwsu.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtpgwjmbji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtyncsypbt.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtlynzjqiq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjugbndfg.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtehdqwxsz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrvuusesl.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtxbdefemw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtkayokjxl.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtzzzatxyd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwbnlpjix.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gtpvppsdwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpcxvqfef.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtgplofcec.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gtelxnmwxa.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtylvgbmdk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtjhvfavfo.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtszdrgove.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtgyqrvysz.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtozwvhcxf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtjrrlvvto.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrvpxqhsy.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtwmwgiumv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtuzqgykwa.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtzhhytcds.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtwenusife.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtprktlpyg.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtwqswusvk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtegxyobct.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gtmbvnmxeg.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtkiglqnql.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtkjktiryo.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtxgiwfojs.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtknmuxoln.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtinnanaml.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtryodnntm.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtcnizrdyb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gtyljvdkdt.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtrazdrhdd.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtbmwdhlqz.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtuhugewcd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtmzrjegks.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gttinfyrth.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtyrmwjxhu.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtildwduud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtkogoisxz.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gthgpcjyiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtttsphzrg.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtekwgxdgv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtztcugtxs.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtgycpypvv.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtoqilrruc.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtnhfqqxjc.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtczvufgut.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtbvtckcho.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtrjtdhrty.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gttzrrxklr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtklciabjs.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtbhezqmrh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtwhorvlmj.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtfxzicupf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gttodgztfk.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gthuthhmme.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtxktmcitx.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtnnfcdqwm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtvoezvivf.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gtonetctdr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjmqghxf.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvqxvnnt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtqrotzydj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtjedlhhta.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtgqgecban.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtlxfjboue.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtovwmdcrf.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtudbcmvdb.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtxyqsfwye.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtbvdnrcir.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtlxfrpqea.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtxemztzgq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtflhpcitk.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtlhmlbmcq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtuwpbqmjr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtnokstypw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtykytspmc.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gtsimklgte.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtvrbkgrqh.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtlgwaihcg.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtebvbfluk.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtrulpnzmj.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtzaaaaalc.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtsaaovxqi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtapxubvpg.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtapmgiqdi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtiuzlvvgo.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtazxvvhny.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gttnddhekg.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtliajskuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtptcuuolg.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtcqevjtwh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtjomhtkma.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtqhvycwlb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtcnxafayr.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtpqhekqrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtzpxluhii.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtvmawlmtf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtnaxfbwgk.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtvdlitbvk.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtbrtvzuzy.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtdslgjxxj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtkeqzjxkl.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtlvcwtrdt.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtwxqsvudl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gteimqkzuo.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnoygvio.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtqfdfnyhv.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtwygsmzra.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtgrrsfqnk.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtwyqfxlwy.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtsroygbef.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtlivbmlta.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gtqzncriin.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtkadhrckt.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtqpnasaiz.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtxawzoken.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtgmwtlnmh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtvhvlpeib.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtsosdlter.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtjjbsvmio.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnndvyvbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtirblnhst.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtvhporbgj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtcfxyyoyf.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtwoozqfiy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtijyggmqh.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphmxpusr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtzgjleqtz.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gtlhenwczz.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtvdlcufrf.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtfcxpghii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtjuyaxhdt.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gtcguuisye.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtwbxyfxum.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtbsnbqjjt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtwbiamqng.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtqebqvznp.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtbnjuslpw.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtfqabeprd.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtriunjkmo.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtbnhroovy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtuckacdoa.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtbnwzwrlq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtehxxorzb.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtkcccizzq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtizemkwnb.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtqblhcxjb.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtomcvspdj.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtzyxdepbq.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gthcwubvgo.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gtppcbmawg.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtfzyuzhct.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtrecunrwk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaisndcp.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gtshyobhbv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtwroadkyg.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtpfkqesuv.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtmhetefgl.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtmdnsmxwq.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtukzzlpgo.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtpoyloehy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtefndrmwd.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtifhlsaqf.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtclnakrwq.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtyepjmtks.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtkozxmsrr.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtjvntvhyw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtrnuxtkrk.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtfiupghft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtihvhlnxu.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtjzdpvszz.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gthlnouzhl.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtacdtfvhy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gtavcsofed.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtrbiubaow.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtsvajsqpc.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gtyxoategb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtvjlxrhiy.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtcvcpvlwv.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtthwkhsms.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzhbixcn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtxdmtsydh.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gtfshwpsms.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtckqzpjxt.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtrwgawemb.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtlbshjifk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtilzqpjcn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtcahtocqi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfjuyygcs.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gthbuuoele.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniqvujel.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtmncpknqq.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtybufbhnw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjlxuivx.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtiqsfvoii.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtzqidrjjp.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gthqdsvddc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gthprfazno.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtpwewkpmk.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsgcptdm.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhyfffno.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtyjchxyul.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtokfzzkmh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gthusieqro.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtrxzhqrwt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gteddylbes.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtvkloca.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtmhbavwbj.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtxngrswvb.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtlhgxpqcd.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gttdpjjyfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtwzhmnzhu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtjmrllqdx.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtfapjzmxo.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqecruxmw.html


<!-- 参考信息 -->