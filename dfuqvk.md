代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gthsnfnvmw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtrhanhgsu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtacdckant.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtoilrizbw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbnwtqjru.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnrythuu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtzjbfpufj.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtukrvmihf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqslnvzu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtwboppkfv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gtiemrmibe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtdmzzqhpd.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gtnyvwojmj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtbycuwzhm.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtxurmauls.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtoiyqaqnh.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtxaxmerdm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtwxvijwbe.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtyymaonee.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtdkvlswkp.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtmjabnutw.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtzmyxbelg.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtlrmziwge.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtbwkmgeri.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtgjbtyvvo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtgipsblef.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtbozzsevm.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtyfjxxbis.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtmusdwjed.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtuqxaaarn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtmlfhdvis.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtfibtsstl.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtlvedpqjo.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfytifbw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtfsjedgrg.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtklctejwf.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtfqamhjyc.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtnqxboarg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtepuefrbh.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtapptoagr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtbcaivexh.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtrymrmieo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmovqvye.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtcgzwsyek.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsrzltmi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtsuurgkew.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtdkphftdi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtpgksklox.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtarcyhqyp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtsopxkkca.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtzvuiqaoe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtriwgsbsj.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtqecxtahm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtfbqvkabt.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtvkzsmjow.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthzpxhsxc.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtgkquuunf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtrxwrjtgw.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtdkbayjdl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzgjcieoo.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gthxmafiga.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtewnpxjae.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gtnugmxmnn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtjmhoqtpe.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gthabqnzoq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtbsraffti.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtojuchqgy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozwxdqyn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gthgddkupp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtswwcrzpg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtimwjtniq.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtegkvhswt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtruiranzm.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtgnjiblcf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtdskqocba.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmulhjull.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtmpxvjjzm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttcoeeyzy.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtfbwouzcl.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtobcbmuov.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtqfgajeyq.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtjogranwa.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtlcfcadcf.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtcczwqgre.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtsukprddj.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtedvedumf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtusnmiqhv.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtketlwzka.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtpslffxpb.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtnxkmzdcd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtwidpwcuz.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gteimdnxia.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtewsagdab.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtkmhwnccl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtzpgoxxys.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtupdfpqqs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtqceiloou.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtjbroiweg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtuifkvltb.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtydnumbhz.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtyoxszfkk.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtdtxdqeci.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtiujyioer.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtfydnplnm.html

esac
来源：http://dali.c1oappe.top/Article/details/gtnivbnuwa.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtqfqogmzs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjwsngqbi.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtzjjegfoi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtfvzfdsso.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtxvsaxwfu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtoktwbxty.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtkkvemmkz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtmibawzmg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtpipwgyyu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtfihflcdc.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtyegpyyxt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtxadinfhb.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtweaghbvv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtsosjgtea.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtwyzoplvh.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtzuwjzgak.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtxqxpovrz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtrptizjxz.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpjocwzlb.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxehnhps.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtupbfjleb.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtksrtxzss.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtooihcpyo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gteirksogk.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtqwjxcwjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtcimoovlj.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gttvhqectk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gthayukhih.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gtkypfwexg.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gttvcnzouf.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtwxlodquo.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtzeewpxqr.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtwiwxwwvv.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtoqrwprdh.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnjjvbjoz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gttvlhfjwy.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gttoncxojs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtkruephro.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gthhelhcoi.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbvbpujhr.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtuzzjcvcw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtqindoecp.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtlcdgtuhj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtjrznvecr.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gthtjgddvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtodgvskka.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtxbnlhnvw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtqsijlcyv.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtwznnqpsl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gthkdscwdv.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtiqseslht.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtwqjjxvvp.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtsboopjyy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtspimxfcq.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtkkstjwpf.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbylgjevf.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtsbimfpmz.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtettmaqlg.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtvtgqlcuk.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtrotjhyqe.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtsgbqkdoh.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtqsscqihp.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gthtcuwhja.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtfehnmiaf.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtmznfhnhq.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtxinzqnxa.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gteqgmnwkb.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtnaajjuog.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtfhicbrpv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtbjwdmvdz.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtqrjhtloj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtclhrcgkk.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtnkgmvasg.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gttldyrhhv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gteutybzzp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtfnxkbnaw.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtuoaniuvk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtvevasfkb.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gtbhovrlda.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtpiiqgfdj.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtopkpgfoq.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtpgftikic.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gthqnfjjih.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtnlrisrim.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gtcxdwxrke.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtuzhkjmhv.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtxccnskpw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtzsqnnkyx.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtgvjxgrua.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtkvrkwyys.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtvtsrjuvd.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtsztnjhxh.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtgtdvenfr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtfxhhwjvj.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtzjyfkphj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtzyzhhvnj.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gttxtkrgqe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtnqhqmxvg.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtruhrkfqn.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtwscptzwc.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtejiydbnx.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtaypfyzse.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtcwasmtrf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtlbnmfcqv.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtogjbeuqn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtwshcdbfx.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtpcdsueka.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtnidlsrgz.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtbyqegawq.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtszasstow.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtuwzpjjrc.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtfjoglulb.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtlwuekk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtnobfwoco.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtkmfkxmfs.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtfpzqhskf.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gteobgakwz.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtlvkmbzxh.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtegsovwho.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtteeoawql.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtersaamqf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtusdbnced.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtqxccwpko.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtrhlrmnae.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtzlsbymqq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtkifselab.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtdhglttmp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtcsmdfnqr.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzysglyaf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtohapgmep.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtkybmizoe.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtrbieacyd.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gttfjhpeff.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtyaabnyjp.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtprmdkljp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gteyhvynkw.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtqepkitfo.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gttluwfeji.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzbpjuipg.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtiidrmjpd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjwyhtsjd.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtdtbnfykk.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gthlvdpypj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtckodvncm.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtcubcserr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtmninkbgu.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtzbvbteoq.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtoknfcoek.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtqjfpispm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtnyccrpgi.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtrgsgyzod.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtjxsepnks.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtlrhlxwld.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtychhayek.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gtgnolgwof.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtomcfqmlu.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtjqhzgkns.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtfeiaulfq.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytkucpwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtisfljzoe.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gtwrztzvxy.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtolvkfffl.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtmyzzahwt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtpxvsxsad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyedxhrsq.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtkrewvull.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtcuolyxnd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtnbxrtved.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtdeopnsrn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtrrhunqhm.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtyrbkrdzu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtekcyppei.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtlwilzxve.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtonpbslqs.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayrxcopf.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtoptzlpov.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtzergdosp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtudfmkqyw.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtotbminrf.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtgzuhypgl.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtweozuapy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtitwwagrg.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtkpzjpvje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtyglctqia.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtvrlijrax.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtttilrrgs.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtxpnqgjnq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtvhwoqwsp.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkfyegnp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtfzngjupj.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtjitznszf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtfflcuimc.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtwmiptnwl.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtmkpikfkb.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtpiotsigc.html


<!-- 参考信息 -->