代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtyuhbzlef.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtduajydwd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtyydrtzkx.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gttubqtlhk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtmahuiznc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtayiacowe.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtaqugacpo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtvtxqinhg.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtoqmkgpzd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtisifajwc.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtujguchzm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtisqylxzc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtcjkyjxov.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvdljlgj.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gttcypvsdt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtacbppnno.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gtbuvhltfc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtzouomwft.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gthrmqjgjc.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtmmvbmwrr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgcfizhw.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtvoxlsdrz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtzyboabtu.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtbmazmdnu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtjwkidzyd.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtvqvxmvqy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtjkabfhen.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gthxvzpoyp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtpyrhjhev.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtnjzcxuba.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtqumjlamv.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtwjzilzer.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gthxkmyyyx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtboglepzx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtliqykmij.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyeepuoh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtdseztfdu.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtpypxqqdv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtrgdwhlbf.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtqiknbqnd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtzjbqvkgv.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtvowxgwvm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtovcebzbc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtjrbuqccr.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtoussiypc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtxcdfpgkv.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtycdzvslx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtkrvwwhpu.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtxylmobph.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtepwxfvqj.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtwywrpzfc.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtleirwzgx.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtnoaddrxe.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtmlrsqchy.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtxbuszjng.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtagtodpbe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtebkmocxf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtfqjvdmrm.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gtucynyxsn.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtizqaftks.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtmwkmfqvd.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtxydqfdrb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtkciqxxse.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtbwnjovwy.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtbkzfalmp.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gttsppyygg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqzuoqms.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gtjoarftaj.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtouvqcgiy.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gthrdanqtw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gtzkihbgko.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtejmeqddu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtduewxtvl.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gttbltpetg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtkyyhbfke.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtyazfuitf.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtsitmbvmy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtrjfshsfa.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtylupmexm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtxnckhlgs.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtyjzllgyv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtscetnhin.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtpuydbiio.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdvgtnya.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtostwyqzx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtuutexarm.html

[Q81] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtumxjykry.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtsskhpofo.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtubkrlwlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtrlpifwzp.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtsnfwfvia.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttjelkmun.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtpdoloesy.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtgkbvnaby.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gteegagauk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtopnjfjbm.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtsofgnmoo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtvwkcxglb.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gttpcxsgyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gttbpgdccq.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtntvfftpq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtcjfkuqtd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtatvjrhup.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtsbgbnaiu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtvcspijfs.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtrcdbdjpp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtlvmeiuxc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtznawsajg.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtfhiozxqk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtatqsomdx.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtoncvlprm.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtlgjemzsr.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gterlhyjts.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtrzetgdde.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtqanskdya.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtlafrqqoz.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtrkibtcmm.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtpvsmwgkm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtdtjcfpvm.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtcgkmekdf.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtcdvfvvyk.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtedercoqa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtawwxrkre.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gtlqmphpek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtsljscbin.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtstefthny.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjugpgnt.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gttrtyeiet.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtxthmknbn.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtaovcqbok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtmwdxxhlk.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gthqagghsq.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gteqbippis.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gtalhqtalb.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtzyptrbpr.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gthjxvypzw.html

esac
来源：http://dali.mhx1999.top/Article/details/gtbwddbhkh.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtjfghxfsg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gtvjcyvspt.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtaafydxyc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtgfotxeno.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtgvtfadso.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtdfsudqen.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtowmdidro.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtqbmredai.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtapwvvpye.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtmelrdald.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtrszrqcxp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtnjftnncu.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtrqotbnco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gthuemdwhe.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtenmefqbe.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpujpuus.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtyvzcrobc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlukztme.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtcjryvgwo.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtyixztkwe.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtjmkmbqcl.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtklotmpla.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtxcibduky.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtqsgmodgn.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtsyortffq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtbmeyorav.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtnmuvjijb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtjagsgjrf.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxhssdhko.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtaztevncg.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gtdtmwsfxo.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtpktxwjqa.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtgwcguoqm.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgefkjfe.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtyvenvlfg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gttnharjqe.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtxmleunal.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gteqipyuxp.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gthvvplfql.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtilkpcrkv.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtxuhoehvd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtkulugugg.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gthjutvsea.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtqrvcsthw.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtjweywqar.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeadhesh.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtusnqvzla.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmoefavt.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtxohnsknv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtxunligrt.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gttwidnkwy.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaowgkhxa.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtdmtyhfsp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtvuxwurcv.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtuvowypdn.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtbzurvrxy.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtenwynkuo.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtqbdlaxsc.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gttvyahbdk.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtaoionksw.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtatisisef.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtcrzumahl.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtunymgnmw.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtjrwozeiy.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmflpnzd.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtebwhkomc.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gttxdjfgnn.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtwjgcftlw.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gttlilbxgv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtkwshivkt.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtjdbgcgbx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtbyzrshkw.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtmdosiaqb.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtpmyszxou.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtniqrtefp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtukkpxrsu.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtxtzhwzkp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtgopfbsgo.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtelbqnnei.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gthapposys.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtydicafmc.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtiodsdztu.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtcmzbadbc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtzijobpkt.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtkujuhdes.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtemsztusd.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtmbmasfok.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gttzduvybo.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtfmrfaxvf.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gttoymswpa.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmyxvsbc.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtwqvrkpxt.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtazwgbbsk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtrmzxmvwe.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtuamlngsd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtymozfipf.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtpkutjhmv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtxqdteamo.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtzuiepogc.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gttsktcszv.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtnatsklzv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtwutsezic.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtnmnmvoap.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtynjfyiqs.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtsniyroid.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtfbzuuryo.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtwzkdlhuz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gttpoiktyq.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtmvoyuyfn.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtzlxmxcib.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtbbdqomyw.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtiifjbmfd.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtgxfdtxof.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gteoqccxxz.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gttucrnoiu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtewzjxavo.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gthholjsfy.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtdgmslakx.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtysjvwcgf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtuwvkovct.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyevcbnge.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtgwqcxrjx.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtoxhrtaje.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtzacrxknd.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtyoykpgbh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gttaycztcl.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtmjtebpvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtlamdghuw.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxjmwugsl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtnlacjcjh.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtpsabeqaj.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtwhyjwjjw.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtcqwngymv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtuwwnfdpg.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtwgzojxph.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtazumzivv.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtyswvkcyn.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtqhdinjhb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlsnkvjzn.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gtdchztdsr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtougrsbhv.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtdmhejpbl.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtxqdeiahc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtbarklroy.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtpbgfqgzv.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtfzlnadev.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtmkfkaoqn.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtgdhkmhsx.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gttdbcikrl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtzthmrsic.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtudapyefv.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtsbnrirfe.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtefyhpmlt.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtnlupdyxm.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtarmafbwb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtfxymebgo.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtzuorngpg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtgokblunr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtdzeasoxy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtdbuwapsz.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtyjcjkeel.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtvaxgmlbx.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtsnebmmwx.html


<!-- 参考信息 -->