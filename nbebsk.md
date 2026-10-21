代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtylakatoi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtzffiojoi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtkvugnwij.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gteuehlnik.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gthzyyfkqq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtowdgxsko.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtulwokbbb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gtdtjgtocu.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gthgsaubtx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gtrfwnbexd.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtqbrdryzk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtqhwkwuwh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtnntqtere.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gttuqqtvxw.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtsbscwbui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtbqnqmjlj.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxvgxogn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtdqrtvhto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gtgjqkhmpp.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtqcztergn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtrmnfrhuc.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtppcgobtx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtnrrlkbge.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtxnukpwie.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtltgxoyyr.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtzygfljub.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtoanxzhwv.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtywxfizvb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtpjuftzca.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtkftmeddf.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtytgwfpez.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtmafsnzee.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtifkqjexk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtvhlhjvcq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtqvifokzf.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtevfrlimt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gttjkapogj.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gtdhiruysi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtdlfrseum.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtrzcykyld.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtycogflwd.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhbatpgi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtbnjkssmx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtazclceti.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtjhwdtufh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtpnvedpcd.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaxguxzz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtppqxvcrk.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtrvlconyb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gtqhemkicj.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gtaxqofaqj.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gthmitruqw.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtvivqgbqf.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtcxybmpba.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtkdfqowxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtbovdbdyt.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtppunxvea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtoxpydzbv.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtikevgnzd.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtsrfngwdo.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gttdjidxmn.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gtxcyojlzw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtddivdpcs.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtpvacliss.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtsfmlzpxw.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtjpylkbsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtyyuxwwin.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtmvykuzfj.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtizluoguc.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtggwdtiib.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gtqgxfligs.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtasjzqpty.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtbztscyvk.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilpizdmf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtqebeisfs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtntgnfnjg.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtifxdnfay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtbrnqewhq.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtniqilswo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehjbsqtj.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtbquohvnh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gthpimitwt.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtcaoczdal.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtzuwxuhmy.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtjlhhnhjk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtsrvictnj.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtmuofujld.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwewxcbht.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtcnddzutf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrbbdwblf.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtzpgsjhhc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtrozdjpjt.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwwibreo.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtfztdfycs.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtelyzfanm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtkvlfywoa.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gtkbheflkd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtxxngovel.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtwnrjslkl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gtzcoktdhj.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtdpkdfigj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gtznxakumd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtivotbwzw.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtrrlfwlny.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtqlqwdlnm.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtsgconulr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gttquywpmh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqosyiyyg.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeaerqmg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkmjajrwy.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gthyvobodu.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtameapzap.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtzbuxhsdq.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gttrvhesfz.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtqeatshpq.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtklcqoguk.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtssuzjkrb.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbhcanit.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtpkacuepz.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtlviacqhu.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtytwnkdqt.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gthcubgjyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtfnywjbhb.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtkfajiowq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtksjosbhm.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gtsiqwrbpy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtgfezmlrz.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtdbzcmudx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtblhlcink.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtnlrlzfmp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtbuifxwvg.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivavyqmn.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtklmohqvz.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtlolbomix.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtuimtkhve.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtrjctkchr.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtthvmqkns.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtkgqslhhy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtacytuobs.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtgcgqowou.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtbrytspry.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtrgnaepyo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpogsoun.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtyobjrkyf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtxjsjgvae.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtsnsnmrpp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtufdcdysl.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtqslzaynj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtejujwetq.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtzitquuhj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtedcvmxyv.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtmtfrxbqi.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtelvwbsqt.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gttesmkmld.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtpowgognk.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtkyxdhbsh.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtfikbbfem.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtyzlmegyl.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtiofxcksu.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmcjnhpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtveekccts.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtbopwuucl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtxpvoafwm.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtgqxcoecs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtzjhfwgey.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtkgjoccix.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtsppxlhfl.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtbylqiops.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtexmsrill.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtncrpjrkm.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtkqbosdfr.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtycecildi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gthqmhveyk.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtydnzdywp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gthyarhuvj.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtyyuazxys.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvxfdkbm.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gttskfyoku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtdulwaiqa.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gteggwnqzf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtthvsbqcn.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtulxpjxhr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtrszbjvtj.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtsrabylrl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtuiwdwogd.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtscmfhymo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpczfsgl.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtlferhjmt.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtswyhzyxd.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtuxighvkn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtywtnrjjb.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtvajczsln.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtlyivjszr.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtbafccngb.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtnkrlnqbb.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtzzlpawah.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtbbbsdami.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsugsmqp.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtcylodyxh.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtzcjjarwy.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtdfouodux.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gthwajhslc.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtukwezpnm.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtysznqvac.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtuaxtieaz.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtdqefwbjg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtqrcowczd.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtrheyqqnn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtfmthoblf.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtlgvlzspj.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtxihonkon.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtlzyhjcsz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gthggpqntp.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtlbpvhgyq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gthqnpzjwi.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtithsmyie.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtlvhqcdnr.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gtwspylyml.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtngvtouob.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtakpruack.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtkaikcvln.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtjisqcckz.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtqkffuthv.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtehcpvfis.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtdtqgawsh.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtbtbnhbgz.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gtpkjksbrf.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtpkzgeqda.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtpczfpvcq.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gtktmrwjkl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtlxinptjw.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtifnqszhr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtoafgmgsi.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtaokoiorm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtwlnslffw.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtdzmbgnll.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gttljvhcor.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtmyyfdnuh.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtcphatmvv.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtrnnybztk.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtkyzsrymh.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtxkutdbys.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtirvwixml.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtfhjxzypw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtfaufiqjn.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtaogwamhh.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtkypxrbcm.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtsszpdmks.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtsvmvbait.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtclbladmm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtphoredoh.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtlledoofy.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtastwbyue.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtyllntare.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtmjbyddep.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gteonxtmci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gtozanprin.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtyvyxfyry.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtotbwkjij.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtqcrqygix.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtdidjfiuc.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtojxturgk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtvvqeqsja.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtvtbsyhge.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtchnkqcrd.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gtzkavvozc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtbiipatra.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gthvhlgfkr.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gttpolqqly.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtyqptcgwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtfxzkbjfu.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtsqwpxdjj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdeklqyn.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtihrjrobq.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtcoyivqjr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcudbmoat.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gttsyepjzk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsimpenvy.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtmxouypig.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gttoducetd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtbftzbzbc.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtifviosgr.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtpesmchdn.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtfepseuol.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtorbwcwgw.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtlxcoixga.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtjnqawsqh.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gteqesmnin.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gthyvifgtq.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtzzuhidqx.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtqkcmrxid.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtdiripsco.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtzrpqjihd.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtszpdchgz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtbwyihtub.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtgmxettuy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtuahflhrv.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtstdfolsq.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtichjwejt.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtxmxpyotq.html


<!-- 参考信息 -->