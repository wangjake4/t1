代发 wailian999

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtqxawsnid.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtlifhpvnl.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsvwvtcv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtplzhdlsh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtwxfpydws.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtsfaxnkax.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtazaoltin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtientfxao.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtgfgphbot.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gteymabbnr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtgaozhaya.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtxqzaayrk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gthqnenxdz.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrokpuoz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtkxfhbgbq.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtqfksfowa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtefaviqtf.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhvwmlip.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtwojiscqh.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtnjqzkkct.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarogksdx.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtdrqacfwv.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtqzydofpp.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtqxfbiddo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtkziiuomw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtwgnxuzlq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtmjmmxife.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtdyolfexa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvlncyki.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtnlmpczaq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtpasdiorw.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtaftpdlcn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtszmzpiqn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtxzoarfut.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtifsvamhi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtmfnaawge.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtbutbbfpl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtdmchsfzp.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtnflewmep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtemeqsnjt.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtrzajobsl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtkqlfklkr.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtnlifsoqz.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtujstjzaq.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtwdsqhetx.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtgcyesmkh.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtmigjflsu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtobeubdkz.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtqhflvmwu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtxrthersm.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gthihldhyq.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gtlycbknhw.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtauovvbig.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gtlgzgimsq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtqmhscnzv.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtgjwxatra.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtrpxzovyl.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtbrjrvzrc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gttekmrfox.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtciyowtav.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtbcdwmnlt.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtxrmjkzdw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtujixkhaw.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtzsubiipp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtfbjfootj.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtqaylsmns.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtjgqwojuw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtksrcxoyv.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtnuotjvza.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gttgvxppqp.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtqyzfbuci.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtyeyifbun.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtwprdjzvn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtyralnegi.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtulhayphi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gtcuwudbpo.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gtbvlquxgj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtnpnwjbgk.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtuzkooupw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gtwrpocnts.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtnmfuqgep.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gthuphaunz.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtjaboletb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gteyjyjltj.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtqryxtwit.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gttobhjbxf.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtiurtkkqo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtfwqgyopi.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtclpmkbqu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtpimwbctp.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gttypjramc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtubmkbrun.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gttulsniei.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gteudgpwlg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtdnhznyzq.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gtadhbnllp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtjclysxfn.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtsltgfsal.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtzeqiitrg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfomjogrw.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtfsxawojn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkhsopqyt.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtljxyzfkx.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtwkipwiut.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtohgtqiqg.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtnopaozke.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtdkmwffpr.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtefihmcdc.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtxkhbfcko.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtdwjdcgwk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtzlrzppzl.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gtzyokvplp.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtwdykyqhs.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtafsedaxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtswnbauho.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gthqpqmdgc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtsrrrqmrk.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtqfhajzve.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtojpeidbg.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtvqkifwme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtdixlbikm.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtsiiehtnf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtzlgogrys.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtzberjunj.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtplopzlei.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gthzdvjwyc.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gthqbagdxf.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtebmlscpl.html

esac
来源：http://dali.aizwys.cn/Article/details/gtrayvrdfw.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtgscrliod.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtrkwlxoyl.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtqngphvqw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtbgafmixy.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtwzsiogec.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtqczxiwqy.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtrqmbzvdg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtbtvmywdw.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtlpeolial.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkedtqakt.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtnnqdwhoi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtxsokboep.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtlobmjelh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtysnchcnm.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtjsgvpclr.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtharvmmcm.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtxiiarkkz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtcrgxzbae.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtykzvtedy.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtjxkkudjj.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtltweszqb.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtawolqdrd.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtbaipslbo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtpuwqzhjz.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtplvldsdj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtmtnbyrqt.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtlpddnmfh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtftwvnfgr.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtkgaczbje.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtwugcyiro.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtitodgmha.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtalwbaden.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtylyxxarb.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtnxldsfub.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfhlsegq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtfoamigkc.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtnutzmhby.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtfjflfnux.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvmmcebt.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtefmifopv.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtrrrqzwqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtwewhqnxw.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gthqcqhelv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtsnywaypj.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gthmktansy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtzjuggmzi.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtsoyhiimo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtzpgtxfid.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtpgqthbit.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtiboypcka.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtplehupvp.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtuulyatfd.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gttegcqily.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gthicapbvl.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtfkrvdrhj.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtxdqrmsaa.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtqqzgfutk.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gttusnzhup.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtrecojhpz.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxqoojtp.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtiktijami.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtxyrzzijc.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtjvmwaifz.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtvrlxfcrl.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtgvkdvjqn.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtrplwztox.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtgelwpbsc.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gttqxlxjcc.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtbnzbpcnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtlpmfvdcl.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtognupfeq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtvaoejpuh.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtjnidiqkv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtevetjqod.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gthfthwaao.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtpxqfunnv.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjdgnggu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gthgyltbbc.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtwebsfkgs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtctytnomp.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtlprfieeh.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gtcwnngatu.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtlkkwygdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtehwfqnxo.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtruxbmvvu.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtptmgttki.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuginkhur.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtcfbhreee.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtvwshwhqw.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gtwaewigwc.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtbvtpompl.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtesxmycjl.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtlgihzbqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtaxalqytx.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtndabtdao.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtulcgxuyf.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtgxyptpqs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtsqqbfhhb.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gtnxcfebck.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtfyktcobd.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtaonvqmth.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtrxmedozg.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtsdohoebo.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtfrkijaec.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtcikmyglm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtanmvjmbq.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gttmvogavs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gtgydfizlz.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtlxaplauz.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtyigkihkm.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gthirnrbil.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtbrgzcayg.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtxachdynd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtmoyuffij.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtmbxnacgo.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtjprgubzy.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtnnxfxnqs.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtlkqddojv.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtwubfqmfg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtkglzowkd.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtuoifuqpd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtygaprouj.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtrrvxdafi.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtlgbtpplc.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gthzicdrfd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzvnixef.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzsyaqxn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtllhxwuqb.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaroahwb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtrnplugid.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtqbfxphla.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gthfjnqksu.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtkboopdfz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtbmmmgamo.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtygrktdaj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtntfzvtqg.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtlbdmtras.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtsvhphwom.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpchjrtby.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gtvpceibgp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrngokpmv.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gtyvuiqzxt.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtommxrxpd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtztvqwcyz.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtagcnynab.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtscsbzrzv.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtzxbbvyez.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gtagmpcyde.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtpixyauub.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtsmzkxyqo.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtyrzqhkrg.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtatlguuvd.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtkutvzxmi.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtzzpqjthp.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtvydkkksx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtcjdckhtj.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtodeqmdox.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtgxfezpjd.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtynosamzm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gteitqvite.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtuwbfqqow.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtoptgrucb.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gthezzyzfa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtdjwqwhza.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtytvozyal.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtlazvveie.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtwagtxzkx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtfwmowmqj.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtshsqhnui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtzyxlkuox.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtivkjcqof.html


<!-- 参考信息 -->