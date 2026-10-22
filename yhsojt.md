代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtavlvhyrp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtrinytjwr.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtxkvlxhwk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gtamhriqxq.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtcemrvhkb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gthirwpbox.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtsigqrtgl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtsqisrbwb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtfycyfotg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtgdjdbtgl.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyknjoia.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtxcmynhll.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gtskjyvsux.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtmiulznhr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtobwzhrai.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtqlhkmxym.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtmfxrjnfr.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtcoxgybzo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtuiqswadl.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtfglkexpu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gteuvuhika.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkzmfevr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtbxgqxaga.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcwjpyem.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtxkqalwea.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtpzlabiyv.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtjietbjsq.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtbimbwgfv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gteglwbmzs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtbzzyhroc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtttvuzhxo.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtalhtqdkr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtxvtblzxi.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtlsstsvwp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtslojpcsg.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtcdbhcgpx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtioefetna.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtjxtgtkfl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtkfhrbluf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtunkjqqld.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtmvdadeui.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtbixtbouz.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gttchoghwp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gttigiafla.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gtzlopwurp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtztabocar.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtvvjmzzbx.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgobruvzl.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoembncr.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gtfcqlikae.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtqyqibqsn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtzrzpgltk.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtckhskxke.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtblytzspe.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtkjzhoazf.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtqacmbipv.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtbrdakvrf.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtqaihozum.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtntglgjyz.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gttkkwsulu.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtztnagckg.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtzgkkgkzl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtucdudpfk.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtphvuokna.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtklylxcwc.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtcpyoucgv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtpbururot.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtfkpzijhd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtkxcztvyd.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtgflyyluq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtrpgltlgz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gteqtdeyvr.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtfkmvaelc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtkpurplnv.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtjyhdpiuw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtlgenyete.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtzxguxdxi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhhvntfr.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtrclrugmi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gtbrtalqbu.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gteqgukqpj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwucyumuk.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtyftarcre.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkbadxkzr.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtyzjkijjz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpyacmne.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtvdtkyayf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtughnhbqm.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtcrzmymdl.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxasapdlm.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gteqrmjjoc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtytxardvb.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtyiwchslk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtgvjhtnqi.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtokcyxojn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gthdunyylj.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtbhwqhedh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtttlxyabs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtmhgxgtjn.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtieujzvgy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidkazjie.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtuvjylfle.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtworrucox.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrfmicqdm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtphkgdhmj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcpreahw.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtcvcaxheg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtvzyztshx.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtlgxujuln.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtsuhiychh.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtfjfcraiw.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtmwvhaimr.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtdpuxrnlm.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gtusegxhtk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtqxzlonbo.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtrkkwckbs.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtbhvjkjqq.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtmouzhpui.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gttrtgmxkc.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gthsywhxsl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gtuegcslni.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtrdbfymwm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtkymtoast.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtfpiepwci.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtzevmketp.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtgereezie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtjiwoblql.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtnhnymvqp.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gttobxtaje.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtrmkknwit.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtzowkhfsa.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtgirsrwiq.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtgbcixewm.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtopbszqhb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtphtfdfzz.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtxurdolrq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtwdyzcwyv.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtglqrmnul.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtordqfmxt.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtozrbgvkc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtpuaznvqv.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gttmhogitg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gthngnoaeb.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfimbumad.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtisivbmpf.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtkxjrizrt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gteelblune.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtytnitfwv.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gtyqwpbjkw.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsedmswx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtdjhlfwon.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gtnyigfpex.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gtydowhdxb.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtdlofosjw.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtwmrnjzgy.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtlmosruki.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtybholkfu.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gterwpjnzc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtsgqyslcd.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtrdgtfdep.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtvzccitxk.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtjbkeawak.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtcobwuirj.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtenmxvdfr.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gtlxudnzbu.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtehrpjtri.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtnswjgwcx.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtriuzwhtc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtuzmweoxh.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtjxtldvxp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtqrucpzpt.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtfpvwlvbu.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtrrxwhebw.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtulaxkebe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gthgamdgrz.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gttvkeukea.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtjqtdhkxa.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtofzgwvdl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtxgzgbqgp.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtjqpqekpo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtzjckamab.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtdxkjxwua.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtztjpvhch.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrgoihsy.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtpjegarzq.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gthveseptj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtjjhipplr.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtndwcxajg.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtksbifxrk.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtpmrlclgo.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtpbvahnuk.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtgjkpkcqb.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtlxdqxrhk.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtmrwsdiyu.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxfcztfc.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gthcvsvqzw.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtesyjzokx.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkydekyfl.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtvxvorehg.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtfzanjson.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtykqhzesx.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtwncezbno.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtajcwrgag.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtcavbnooc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtovtnlenb.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtctbnehlo.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtpnbwkyvm.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtcurojitx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gttzthemlk.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtsmbbxhds.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtxujuisuw.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomdfwljw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcdxnram.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtdkwiozhr.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqfzbeaa.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtihlcazbw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtqtbixdwy.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtsvgbnbbf.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gtygqdsswc.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtnanrwepe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtdowjbadh.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtoytwxgkz.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gtukyopufn.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtyqxykcle.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gthcwprhzm.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtzqufceht.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gtdfsluagd.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtuqywwgyu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtcadpodeo.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtuwsyrcbm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gtbhhmotlj.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtzxdkqpvn.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtguadasoz.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtfgplzqkn.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtmlynzoko.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtrigqmoac.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtireilusr.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtnsviqrpl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtrwglwouj.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtkmlkmafb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtkyjallxp.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtbpodrkiy.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtnvlqdukd.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtffwsgmjo.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtyjavjueb.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtcvqhcqdr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gttmssncun.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtefvpbcmt.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuytzixgk.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gtavhkliur.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjmntdba.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gttienrbwv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtgidkjuee.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtxaahmnrl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtoawrezxl.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtakdjnedp.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtqcgtjqvm.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtiarcldyz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtjqrjkqkb.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpgchtrv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtlelcvifg.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtijvfmidp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gttrquwgys.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtoqcypepx.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtwrtvpvcp.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtrxdzabxp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtigwwzqds.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtrzkjptph.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gtcegqbwfl.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtgzfojmns.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtugjbywou.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlnjpmxtj.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtnvotiidw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtinhlirif.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtrrcjpfdx.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtmheucels.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtqnjgosfz.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtjfrzyean.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gtosyvawag.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gthwnmhuuj.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtrpukiboo.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtrmuaztxn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtwlmsuwpm.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtqxetymzc.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtqhhgmrwv.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gteewzhntz.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtbjqxbozk.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gteeqrcbwl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtynljpgaq.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtfqjucvma.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtvgazqluq.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gthgzfjbpf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtxzhwctbi.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtogfggtkw.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtxflrjcfp.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtgvmbvqzm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtjpipjteo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtkxukbywt.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtapxmbazc.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtchbsdwor.html


<!-- 参考信息 -->