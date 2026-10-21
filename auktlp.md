代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtyyxaerkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtvksuxdic.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbsngobo.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtunwvurwi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtrxmtdvvf.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtvkahdmrv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtugpbbems.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtbtipbwtf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepeyjrjj.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtlzcucbmw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtgvmlmwle.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gtlwdufsfo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtiodkyssd.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtwocfxsjd.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gttgyhlsbx.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtneygbxjb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtziqfzgnc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gtjrdhbpgw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtfaessmmy.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtcxcjnwbh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqycpdzwa.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtvhjthtew.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtlffvslrl.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtytnfdgxq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtavslblfj.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtdhwzmraf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtuovzhskd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtgcbvucag.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtqbsfsqdf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtfimfwkul.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtbhvtuqtw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gttqhupsmc.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtovvasvcm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtxkixdrgj.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnobiapcs.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktbhwens.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtquevqvos.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtkskqfwje.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtgvywgnzu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtlknzbdvj.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gteqbzrwox.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gteefknkut.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtcyluffhc.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbduuxho.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtkrrlhilf.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtdjkyuvkn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtaxoolimd.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gteoxzqyve.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gteexzknpn.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtilqqnszw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlyxblcn.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtgobmkovo.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gthhjgahth.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtqedoafcx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gttbkgnzal.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtpeihgqqo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidnhvmiu.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtsbucsfza.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtbbmszzzf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtsdxdhxta.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtezyenyod.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gthcawskun.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gttfpvlafp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtuuwflpsd.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdtvuyzr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtwsowolfp.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtyuqxshnp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtbeseqwqk.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtrhliehpb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsgqknfuz.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtpvldxoab.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtbtrijctp.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtinlfoyxw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtbsjhcpnx.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtqfdwhrjw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtixahztjk.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtmjmfyvqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttmzisuro.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtpdfhysfc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtmmjjmjnz.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gtutzmhpzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtwevlyabj.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtkcigrlaa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtnfvvupbf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtuxuxehgv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtsvognhmh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfcxvsvkv.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtjgusgqpe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtyaobzcdq.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gtijvcqytf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gtgkrrgksw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtifltwbjl.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtyyqjtxln.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtesbbdtan.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtudnnhmgm.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtmmhldjqp.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtvzbwjcua.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtccbpdbcd.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtnkzfmsku.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtjtiprbnp.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtdynwqtui.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcqjxtxu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtkgssyrzi.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gtgdxrrnoz.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtxpsrvzzd.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gthetumnur.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsdoslvh.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqajwhhb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtcvijbavu.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtxjjpmzid.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqnhcxnc.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtmieeuzjh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtifhvnnaq.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtletqummk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtuawhmnzg.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtapcgnfds.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtpfirncqk.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtaiveatxv.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtprggipfd.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtncttqfyt.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtovwerjle.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtvqcalgma.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtnmyjcemh.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtevhkojlz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtpfopirby.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gteiknvxsm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtfscmptii.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtrsbflczx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtdruptsmo.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtimhbrdex.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtrodleemx.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtwbyvuekn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtpvvfhsyn.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtvdujunsv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtkejkbwlm.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtgepxhibk.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtuditlgin.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtsunngagw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gteqjiepdt.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtdseucyeg.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gttwskouzy.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtdadxmudx.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtfegaosjn.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtvlxivwzm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gtzfnwafuv.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtnbomoufi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtbowxikzu.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtbumssjqq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtgszkfxgi.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtvvuahpzq.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gtkpawopnw.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtqpalswki.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gtidifmijs.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtqjhgoeto.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzmoajvc.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtwkwyjlhx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtmrkjvugg.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtlajcnnig.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gtlbsshdnf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtzknsuoqf.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gttmjodoyj.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtbizyspxa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gturitcxed.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gttqcubbnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtknmsmgeg.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrirmbnqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtbjiruelb.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtkbgrgdbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtjilckhyl.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtbrprhhki.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtycqrqpyj.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrudlvvlm.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnarjbphe.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtbiswftai.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtwwyjtogd.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtagrdetgc.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtrjxnnewb.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtwekbepbf.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gttgovauns.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhtjnwob.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtdjywsqnm.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtszmxlrcf.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtaqmxrlrz.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqsjxrnc.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtwjioxdsw.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtfanszoka.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gteuvgjtws.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtenhtgyfe.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtffrlnvfw.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtttztswsn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtuykwongn.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtupudqxqv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtarrqlabv.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtwvftowfz.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtqmrbniez.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtryfmkpch.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtsjukeenr.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtbkbisdjp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gteqexnkkt.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtfiuypgtx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtxnzwcwpw.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtgdobqlay.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtnlqehxjj.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtkruosqib.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtnuyeavag.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtnvlesdpv.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtrqwbonsd.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtltyxldbz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkqdeepv.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtxtvyfsfv.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtzguiyxbn.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtbnchjcml.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtyejxezdl.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtcadehmdc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnhgmqkp.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtmehvzemb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtauicpdev.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtrkbofgfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtycixewey.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gthvsiiqqo.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtbgcxofbc.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtqkylxmfv.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtwsxdazyj.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtfspnvrgn.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gteuvkdget.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gthmevygwg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtqiqtihmj.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtcnglgjxh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gttwauqlhs.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtljveopsd.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtmkoxkuwj.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gthxnlktij.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtolbyffrb.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtiewjfwxv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtgxvxcmks.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtpyczdkmh.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtqnnzkvvp.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtwkqtlsgx.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtlfwxtkmx.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtjcftmfow.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtihqqnocy.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmajrcob.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsainbtt.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtpjtzqrkn.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtcticrrzf.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtymshdqyg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtxmkmhpeq.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtueflmeli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtmgpwwygn.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtzqnukize.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtjncvrdbv.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtttntngsd.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtbtbhxaxl.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtgkggdpbu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtsjsvbbjq.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtiusschgw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtrfiewhzx.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtdvcpydyj.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gttlpwbkxy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnzghfjfy.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzksnohzp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgkjofikm.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtxxjifcbe.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gtcteyswei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtlasdykiv.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtkwanpncz.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtcyxqknoq.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtrqvmbiqg.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtsvpolrgn.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gtvfrompyg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtvdmiomqq.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtuftnizyb.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtnqgibqkq.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtfnhellvm.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gttboprzxx.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtntigvrqj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtinancyba.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtwejqcwvd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtttreruyr.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtgcvqqblt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtgdxyariq.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtjeoiklax.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtvczfpyha.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtldphalmy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gthmlpdrcw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtzdnmzukp.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gttsxsnsow.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtbsipotxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gttphcqwpc.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtzacrwlow.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtccimpluh.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gttjxfeqig.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtccalheqc.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjltrpxpw.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtzozbvfom.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtogibnsub.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtxbdgyfti.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtetiawybm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtxqafgbrf.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gteapjafbo.html


<!-- 参考信息 -->