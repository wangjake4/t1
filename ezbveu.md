代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtuyhtpjbd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkzgknun.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtwzklldgi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtpxrmkaru.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtiglwmtvv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtlsneugqz.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtavexwnwi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtzsbtkxje.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjivqtvho.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtezvndwie.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtkcbydxcy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtyhlibowd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtpswbszsj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtfpxzncty.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gtzoxsfvow.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtcviddinn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtukurglmy.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gtmqdeblfw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtidtbyafb.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtiwrapjfp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtctqsuxxy.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gttdgzdjlq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtsddoqqfw.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtsfynwznr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtchxsueek.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtvlgyqiji.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtwtpebdxu.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gthzjdiclc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtaydfmsrs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gttmstpkto.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtuvrikozx.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwddhtpmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gthdnjzrmk.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtglqecjpc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtgewmddgn.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gtwrnfmczl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtbwzhiuyi.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtsiceeapc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gtdwdtqmzw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gthpanhkug.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtgpvwymjq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtoifhfifo.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gthptjmgkt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtnnxizfge.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gthzqfphrk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gthjoetfyj.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtcqikpcqg.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtyqnmzozn.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gthekekkhc.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtiahgpjlj.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtwmhfnjle.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gttkunjfps.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtwbacdkdr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtzfregxwm.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtyictzmxg.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtgukfqmdt.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtllmeeznl.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtmoeqjpro.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gtsjtlmamw.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtiyiorngg.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtynasgggg.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtxgfbegkw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtgputedif.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtozqejgch.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtolbiymtr.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtfviigfpf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqthnjxke.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtsgzherrl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtemhflwoa.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtspdurgxz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtfkntpowx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkyieniq.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtjwigxroo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwizgydv.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtxlwqnssm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtkygcgtnb.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtrcotfuft.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtwrzdbulf.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtvcdrvfwe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtzpbqsaul.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtwthezkry.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtjhesnoql.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtmnrfmtbm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwotzyto.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcuicgkds.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtdqnfyawm.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrgrsfzt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtlqsmewiz.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtgaezhmpy.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwytsxvm.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtwihnnmoi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtjprzjkza.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtxpjmnntu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtgjmlifwa.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtyswmpgsp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtriqvbunw.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gtkqwnahtu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtzykdeant.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxosmtzid.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtaduanltw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtrafmyjbp.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtfwozlfri.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgtuufek.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzpimckzn.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gtvmfpngth.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqszfumrw.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtneozitts.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtecxchhzc.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtqzkvhxbn.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtccjeggdd.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtvhbtntqb.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtngtxrteo.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtytxvcjmq.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtdeuyqrpa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtydwntzmh.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtuuuznwjh.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzmnudvlj.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtdughnxbb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtiqrqsqmd.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtcczthnuv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtwfhjsmwt.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gtzwxilpmz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtsruzpwcp.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrfowawg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtbwwscqqs.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gtcriozhpn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtjvclfhhb.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtdindeqid.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtbbijvtvs.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuwgnzbq.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtalflgznk.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtignnktvu.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtszljvwos.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtizilhval.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtcthwidhq.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtscmxmmon.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtikrwpwlp.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtmiixdota.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtrltxwywf.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtmktmuvaw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtchrrpbhb.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtaedylhew.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gteuhdrwgj.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtmdyaxccw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtokatofqt.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtlcffkcqq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtwnkxznag.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssrkdqah.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtctgnyxjg.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtgaznftyc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtesppaooh.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkixbuiib.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtblknnydm.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtavhzolmf.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtccrguxvi.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtlmxqdjto.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gtnedoruev.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtixjgadop.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpgcsvhw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtxyarcenr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiovvtfyn.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gttdnozofb.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtekfvqucw.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtvtqmaodj.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtaiindyky.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtrykxjiaq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtyahthfam.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtheskcmwd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtcgqqfwed.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gthjjamzai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtsuyhgocj.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtmvifgtyr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtyfhgihqn.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtwfjbccqo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtdahuxkng.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtsqgsdgjx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtyyevxpoh.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtyretrwoo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtaazjoism.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtctbhsyms.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxinkj.top/Article/details/gthpfodzpm.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtsnzwbzvl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtlfpmduku.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtnqkgirsv.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbyybjyi.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gtaukpxzmr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtdwaedwgy.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtgykqenmd.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gttdhousuw.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtreulfaui.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehasuner.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtxskuctbn.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtvjffitqi.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtuszxinrv.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtpkbzepec.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gthonulrnn.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtpixtshnj.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtxuwwdcmz.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtokouycjw.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtodsjbdbh.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtkhlcenus.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtucygzyzf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtqieitnfn.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtzebldpln.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtpuldsqaq.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtqknhmlft.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtqalottdx.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtyojloryv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gttambcuge.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtlmgbzmpo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtsdlqrruw.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtohefjhhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtrofyitlr.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtqhkwiete.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtoplwwfyv.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtmplhaodm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gtiorqvnih.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtdwibqtzn.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtezoyzuvo.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwkxktag.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtfhayhwca.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtjncqzero.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gttvcszbps.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtcryitxxc.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtwvqflfva.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtrrzgcyjg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtinuzkivc.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtpidrzpya.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrjwrcxw.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtclgdqlvc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtsjunxwph.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtjeutvuzo.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtqzuxncej.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtwhmsevqb.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtkjigiftk.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtrvydvrjh.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtalcloidm.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtnspyiveq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtyvrkhpmo.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtxijcudcq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtaqzyrtqb.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtirwifyhl.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtmpxyttms.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtwtnghtxe.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gtljnkfbxx.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtlfqqdizz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtypkyrglu.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtsfgejgdz.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtgyitxcut.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtomvfkzzo.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtjtcljsdp.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtxehoecjh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtktkkznxp.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtktscqdta.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtxqjwgutz.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtffsstcxt.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtgkivtpzw.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gttoxjqbcc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtfdykabgw.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtezjwazly.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gtqldtxfel.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtbptmyndf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtdvttzlvu.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtatytthel.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtvlqqyivo.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtwxqpuwws.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtdyyfytwq.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtzqxbyobp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gtxxfixfnm.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gtmmppdezc.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtyxexjjce.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtihuxottp.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtgbkebtjo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpkzjhnbg.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtmzpxtkdy.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtrhudkdjt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtirmunhtb.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtwruqtekm.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtlltilzla.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtbhkvpahu.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtzpeiyuou.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gteghqnjjl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtriydlyig.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gterzhtjds.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtrotpzzxj.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtducxphwl.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtrgfsoyyo.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtzjmjsmsb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtsyzkzluc.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtnrffaeko.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtvixdrbgt.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzwdhqdu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtcdginjgx.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtprgzfrni.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtzhzxbipm.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtnrzgwxsd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtkrdirxyw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtlevcqrkk.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtdnswzdop.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtosoruedu.html


<!-- 参考信息 -->