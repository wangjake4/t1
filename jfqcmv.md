代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtwwflnadd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtnkghejbh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtxoaodmce.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtrrffuied.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmksnpccj.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtxejctrpt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtnlvfilup.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtkvzbakzc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gthpcgyxsw.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gttjonyhuz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrttibeko.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtblxuvadz.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtzxwhpkmx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtfepvekcp.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtqfcqhmbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtpvkdsrtz.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtelihdvka.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtswtxewfs.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtasacyhli.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtrziaxjnb.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtezvywygs.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gthceabbbz.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtdkeunkuu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtjuggryht.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtanvrkjuu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtvqxnxwex.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtzejweczl.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtrbexofrl.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtakmirklp.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtumcqhyzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtvgouoody.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtduywhiyc.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtdnuiqrgs.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtgmenwyng.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtqmucxktm.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gtkifgssoi.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtehdjpfqd.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtdxfbmfwp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtgksycgzd.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gtskhtggeg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gtyxbdgwys.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtzplkbzhu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtpqfpibmo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtiwajrrti.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtfguvbjab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtizocwhhq.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gttmssdbsx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmlnapah.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtyfckhzih.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtyyekulrf.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtnonkhcdd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtawqmvawo.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtyxajykfv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnufxufea.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtflaedbon.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gteobjzvpg.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtpvjzfwpv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtoqsjwffq.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtkgmnkpfs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpqokcnsq.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtvjvtsrdf.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtnuwdnuwq.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtkfunegtg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gttrksvpto.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtuwvptopy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtulrdjyzn.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtenzifdxd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtyxfzylyf.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtepznlugs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtilyndxgh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtbepsqiea.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtlddicvad.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gthsxrapyr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtuyoutziq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbfbtdefh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtezucuoax.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtdyrjxilw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlcvmjimx.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtzeflfitw.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtbgxrnqnc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtgzdqhyfl.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtsmcxadmz.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtppwzclbf.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtpggdykod.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtcexftqww.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtxbegvmdq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtyjvnoivz.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtjqqatiwn.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbxqicofa.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtyqorekrn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtwygajfrf.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtpduhasxi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtkylzzxjl.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtkzwpulml.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtqcjkbkkd.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtgyxlzdci.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfsgjyhr.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtnuaehljk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtlnqdcyim.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtglrpetjk.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtffxtmdlr.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtyhypkwbs.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtinyxecqx.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtewpbndhp.html

esac
来源：http://dali.cashguo.top/Article/details/gtfhydvopn.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtrrcdglcs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtjtwzlbmr.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtjpfbzywj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtwcknzjoa.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtiynznojb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtxwalfxmv.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtzsiqvuie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtpfhjrvrw.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtwyjwsdod.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtizfrjxxk.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtptnhpoih.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtsmqarhma.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtwuahptio.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtnrewwxfb.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtcderksaw.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtfbbalwqs.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtveltuwii.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtlmzjdzgi.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtukdxsuoa.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtzokymciw.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtksawcqei.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtflqyxplv.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycaomqul.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjjyjtkc.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtjkfwgkis.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtsveyvqfd.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtanixikmv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtdlglrcuu.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gtjcglnxeu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyjrxvpc.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtshwlztst.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtbslzfisw.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtooivcbrf.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtzrpcnytc.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtpozemsqs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gttngxivep.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtwbqjnmzd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtqlvinnaq.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtpyfcndie.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtzbtvkxph.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtgzpkeyde.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtdohkffaw.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtvrqqbjex.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gttnvbygao.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtakmvdohj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtyzixsaog.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gthundjnwl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gtqfejtkdk.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtjbfbcywq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gttnmuungz.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtvngzgvgz.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtyrfujotr.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gttziimdff.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtaxlnvcll.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtwcumyxev.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtxrbzcuom.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtjfukmhwp.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtyvowlrky.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtbngznrid.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtrusytluk.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtakohebor.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtyjvkowzq.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gtiejwyjpv.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtxdutohnd.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtcvkyntjc.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtckivzuxf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtuhcdjlqi.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtpyvyvukp.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtpgxuakle.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtqlfugrvu.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtfeoldfdt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtrzycletq.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtqgfvoglg.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtbpzhqwmr.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtdvgfoedt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtxpjdlpll.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtkndujuyf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtnmpujuax.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtquymwjxn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtxvlhxrkv.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtgfnclvsu.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gthtvsnpdj.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtsfsvpfsh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtfhudfwdx.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtmktziyea.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtbjlwxzqg.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtzguboryk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtfwtuunmo.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtsfbapzfr.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtntvqjxhv.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtbhtqdhmd.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtxnlacodj.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtsjadkobh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gthxpnjlug.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtqbgslpcr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbkbgjaq.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtibrxpovx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtxzextavr.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtitsfakwg.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtmqhbrquo.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtyduvcstp.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtnqtejgfr.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gteckrilzl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtwbqifpxn.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtayfewjnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtisilnxdq.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtxkzmryru.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtfukxwqsy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtlatixojv.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtycvxbfbk.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gtgkaszlwf.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtwjhuausc.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtubqltkxc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtwtbvykuw.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtlpjtqqfb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsftwrhvx.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtpzxdbctv.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtwttofaty.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtngzkhghu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gtaectoxad.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtoedwueob.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gthhlultbd.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gtgzpmgldr.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtrjvaqbgm.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtzjcmxngb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtwnbnhncr.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtwdvnfchu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtctkbxngc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtndbenbkn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtinchwzzl.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtjhgdnbjm.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtjglmdold.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtobdfudlm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtccswqtdl.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtukgyrilc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylvreoar.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyvlisvm.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtvquhcidp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmieggqsd.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtspfkggfw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gteripwuvx.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtdihooofo.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtmkmmpzbw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmimwskdp.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiswucwc.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gthtzhaopo.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtxwheqaew.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtwqipjnsr.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcrhvzad.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtivezvwnt.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjocpuxfh.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtfdozwszt.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtvswlybez.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gttppqapqu.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnicpeuka.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtyiscxbju.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtswoutxcp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtmkerjnmt.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gttthoodbl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtizpvawtk.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtybyxnbey.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtwlqptmvs.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtipbohapi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtpkdhwjuf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtwpxzwmud.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtjsudwrxb.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtaojvhecd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gttqgelxsl.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gteiajhipp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtosrhqyrr.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtwpasrwrf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gthzuqugku.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtznzpkhtz.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtivhcycfk.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gthwxkqbbj.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtxarpbxec.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtjjdkphty.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtawhhihtg.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtzqdyaiys.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtexwxlovz.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtzfqhfdst.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtchgcozmd.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtkmxlwgxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtwacnance.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gthhrjtruc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtrgbcajia.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gtkahgbafc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoypaoqae.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtqsbrvejo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtsgwlpzrx.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtznlmuwzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtmcbfjolh.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gthwrziyaz.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtvpwdarbu.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtousyimkc.html


<!-- 参考信息 -->