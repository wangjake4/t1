代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtswznmjcw.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gteikghmii.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtttmjwfac.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtznjchvhd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtybttzymq.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtftuhzktq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsottrfxk.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgxsgake.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gteestgaqi.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gtyryxnubx.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtuzolpeir.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtmxqbhvew.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtujcsydyj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtprithhfg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtqhxgjilo.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtltmoisjk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtrcgtiisw.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtxzrqpbqo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtzykmskhn.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtrwijhkpt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbtkmeudp.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtpxxdbquu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtgvuiquor.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtirceeyex.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtrtxhpdiy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtdthxfkss.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtdnvkfcor.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtuwgarzlk.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfcddabv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtzmclugpu.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtslrmstzx.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroifofhw.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtagjfwxdv.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtbssxdrru.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtnqwwocyu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtfuxjeuvl.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtamrdpcex.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gttiriywvh.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtgtdenqzf.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkxlbgky.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtlmnnckdo.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtmbyjyiyl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtavsbwczd.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmhgbeas.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtsufojufi.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtixaihrho.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gttxboeefb.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtkpfcpwki.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtgznjydca.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gteqrveafb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gthuvfvkwl.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gttectmfpz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtsoyppcmu.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtwiixiynu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtxegvefqz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtemzgfhfa.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gttiwyzggx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtgjfcwztj.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtcogmygrp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtbfumaben.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtvewrnfjo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gtafigalba.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtwirlosas.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtpnbiogdo.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtvngmszcb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtxlntiege.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtylcmrfub.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtvumgotlw.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtzvrvrhhg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtyzswmfmq.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtfjzexdmz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtpkzzcnwy.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtyxjijjop.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieeunomb.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtcacrwbsh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtlgrwwteq.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtqiozldim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtkkylwhpj.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtorcijfhu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gterxoaqfz.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtuanhxpai.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gtbhnyxbpx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtegnqhrgq.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gthbdkhrvo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtmxixxydk.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtgjvebuxk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gthgnufina.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgucajwyu.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgjsathw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtriywrdfo.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gtzziadyga.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtmbzwrmyj.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtkxtnkdsk.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtsabehiqa.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtfwlbwtlf.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtzchaxhkd.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtcafyijrg.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtybxsiigt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gthceihexb.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtxrikbmat.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gttnlajtkv.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gteekryurm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtufhjqkur.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtaoqjcvnf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gthjharrgg.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtrxvjksez.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gttvbaefml.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbzohncj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtephkpujv.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gtimvzygko.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtzjblcs.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtuwsritsy.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtosjkwyeo.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtgksqpacr.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtlocescfn.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtoufphatr.html

esac
来源：http://dali.cashguo.top/Article/details/gtwyabrwap.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtjerxbwob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtxbluoomn.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtjpjklvcq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gthrjnuwqh.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtictjthwt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtzmoirefi.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtcyeglqxb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtebvaqibe.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqpycqsl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfzwbvsi.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtlbozzwss.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gthwbzwtel.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtcxjudric.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gtlwmquigx.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtxhgjxjss.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtuezliqcj.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtljkijckr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtlulymmha.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtnpokvlef.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtbawwxshs.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtnrvpzjll.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtwxmzezgz.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtfbslknir.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtsdkoxixp.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtuqvtjylk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtmkjvberm.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtmonspfmb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtlxfrchjg.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gthtcfrjym.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtgmvctrey.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gtzxrnknlg.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtffbgmgzp.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtbaqgtfsn.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtjcorpjgs.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqcligqg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gtekpgxzmr.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtaohpzqnj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtucccnpou.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtuyqawnzt.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtbwnsbhhf.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtjtsedahh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtgnyuhpbt.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzbvhguy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtesbwjnyg.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtjybrvmlu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtmavuhkdb.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gthzgatddz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtrowesbdp.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtpdzdfurn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtqbjxlgxd.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtmlabnoxd.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtvjhhizfh.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtevsjnuor.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtihhntczc.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtykcfxyyq.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtihatixrl.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtgxsynzlo.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gthxqhbsro.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtnpdxdjvb.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gteappoqiy.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gthyvxhcyf.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtdqxaoicf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtbuximybb.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtmfjrzkno.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtvkojpdej.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gtspejklki.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtxblytbkm.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtabszafie.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtyapzbafy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtgknhkjxx.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtqcstartz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtawpvcxtm.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtbcgqrluo.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtluqcvuhr.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gteslmsesy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtvpiflvuu.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtyyrvapwe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtksoamkjx.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqfuspgk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtxdkpmxxw.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtszstxdqv.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtzryocllx.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtjnovrltl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtdnwyynxq.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtnunvrhzx.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gtuqlklqpq.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtunponqea.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtvlydmeil.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtyoyovysu.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtraakgfaf.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtgjgjnruw.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gtkljfymmd.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtkuanvowd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtkzyqohul.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtghlglviy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtcxumsktk.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtlpzuzinf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtnmhsbfrt.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtcgrbspwd.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtiqgbcrmn.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gthnhiobpi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtptxlchai.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtposihpap.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtfsyjidvp.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtofedyehn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtgudbqsuz.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtfkkgjycr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gthuyhihdo.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtftgnlkmr.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtxvqwwnfc.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtwwiouqre.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtoshrvnho.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtwobmsgea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbcglpvle.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtrcetczsl.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtfxmzumnc.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtdvcjlmgi.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtyldyudxq.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gttxzneiao.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtqgjjijqc.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtemyrqiof.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtgilbscys.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtugmbkqob.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtvdoozngi.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtrtqppcyr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtdmvuozxa.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtbyvkfgax.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtkfsesgyd.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtyaatsptn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtngupshcq.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gtqypknmxv.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtgktkrhif.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtipcyxarl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtikopufxk.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtyioqnnso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtnowdjdbv.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtaecwgioa.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtenudjshf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtiplrknjw.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtmzdjmswp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvfehvozd.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtohelprhb.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtyomwnmgv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtjikdlzxq.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtamlhtclj.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtyqfrjvkj.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtlvtiqnwa.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtwngzqvzf.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtrjoyhjhi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtjvwdcphd.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtykejyeqd.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtynfexful.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtpttqvomg.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gttnhbjvab.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtuwwfibxy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtuxtcznrc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtgjdojhwn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtkicrhexo.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtdcwmxnpe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtdzmtguoh.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gttesabwft.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtrtpwfsxk.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtjlyyieql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtoyonvdxc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gterccadqp.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtdtcgefjk.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtxgcxqblr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvcpmohg.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtwrokbxle.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtbtvstogb.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzgsetsz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtpseleexf.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtzxvmtzyn.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtrwhoshzz.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtlgyidowz.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtfpnxbazw.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdawyjvaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtcrfiknzs.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtmlstlxvp.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtxkokuasl.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtdqxydrqi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtjovrikro.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtqlzrhzse.html


<!-- 参考信息 -->