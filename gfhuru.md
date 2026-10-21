代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtewjjtmyf.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtznbiyswo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxlmmlrvq.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtccmqortt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtnskjswej.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtjfkkdste.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuuzoawz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtbxwhgzux.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtfcsqqckb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtgauavclg.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtxrauxytc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gthcopgkzi.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtrhrdofnt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtikkcmsiv.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtkmzxedzs.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtwhmukewt.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtmyfdrggn.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtvjwnrwrv.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtdvhcvpul.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtyvkxohpt.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtnqrhgetk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gttbrjlsta.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtmvzruuzp.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtkidbeqsi.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtagsntqhg.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtkmiaqcyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtzfqiraep.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtkbyrrnco.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtpapjmckl.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gtmpjhmcth.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtbqdgjxnx.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtkbevyekg.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtkiygbsjy.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtqsjnuizm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtfnxnnukv.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtticxmspr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeotxsam.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtaqbvkikt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtrsxeyfsw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtafyhpwvm.html

[Q76] 按天统计
来源：http://dali.hywenlv.cn/Article/details/gtetsjgvku.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gthbapyuyy.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtkiutmgkc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtnprjlxyl.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtwgmzmlma.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gtuolhyeec.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtlwebshkf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gtaxqtwkzq.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtpzfeixkq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gtzsvgyqbz.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtbrwkkaqi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtuvburzeq.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gtpackjwbo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtggjcxaas.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtsuoztgor.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmloqgkjq.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtbhstugfc.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthrsscxtl.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtuztibatz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtzbouqrut.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtvbfnfhtz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtqmufchqa.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtbvxhlqdm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvsbbarj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtalqcpwka.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtbkpoglil.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtdvnxuiik.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtwykttcwr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtaxihtyck.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtgrbmelwx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtzdflaito.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiwmsmmjp.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtfcrzwncj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxxttqhmb.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtpwiwhcwc.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtcgtcyhnj.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gthkeescaq.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gtgkdbanyt.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtacwnemii.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtpzocuewv.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtaixkgmvg.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtxkxeodiu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtyrqbqtsn.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtivgqzyuj.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gttasolhxs.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtxghszpdy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtjmnqinjy.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtufiozxxe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtufzgmwkc.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtnqrwzzoc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtgctvympn.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtuthkbkog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtrauxcasb.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtgzkegrhr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtgvzfyywp.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtebpfcqvs.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtahvmrfsc.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtsyfaujep.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gthwxlzsvc.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtdbbogisx.html

esac
来源：http://dali.cucudq.cn/Article/details/gtroajqxfb.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtcdjcrmzk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtinhgqigi.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtvrlcneha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtghzksddv.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gthtneouru.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtednzdppg.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtfpnuydve.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtiolcdjop.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtxxwvvfeu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtyzwpiyzi.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtnkhdowfi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtpppxltby.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gtpjvmaccq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gttuffqpkm.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gttmzdwpju.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtllneegpe.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtzqvjgikp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtvcwjeyuo.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gthgjuzagt.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbypadeyd.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtuvdzzwur.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gtxroeqfen.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtblphmotb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtlcmnauet.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtqqffgebv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtlxfvttdi.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtqqkjhizw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtjokboioq.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gtwqmvueqw.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtbwqebnuk.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gthnlulmto.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtzkgvpnyt.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtjgleliba.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtfdhkcqoz.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtzvyqfait.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtukpbtond.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtesyjrtik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtycntihnc.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtasfbzqcp.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gthvbmgiut.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtyhwhbehu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtygwxczvz.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtzxlkbvox.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtizttdzem.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtvqfhvorf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtddikwynh.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtmaoyxycg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtsknhftan.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtqbxprpah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtevtnofuw.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtdjpemolt.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtvoyzmaoy.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtoycafqps.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtsycacfjq.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtozlthrcc.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtawyqxlbt.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtridiyjwc.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtndodyxpw.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtipiazyvn.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtpugmiswh.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtgahfbwub.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtvteiojts.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtmjpvqehy.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtzdialitj.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxjxvyus.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtbgipssky.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtzgavdkrv.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtaowundcb.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gtaflrspxv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtlogimaii.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtkxyfvbqx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtdrdgwxkj.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtzdiiopes.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtdztbbxmb.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtswwynupp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtqxdujwja.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtfblpdbqf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtzhnfcpao.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtqyaalysc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gtezalsnjn.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtwolvybvp.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtghdbslpt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gtbqcxkzxn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtaegiryry.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtdgjqolup.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsnclenl.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtiitycpkd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtpcyyzvwm.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtfoqhexsq.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtvmactxgs.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtvjghibjj.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtdktluaze.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjzwmpnjj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtwqkczodc.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtetwvtplu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtfvewmott.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtkbfvnyqz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxypuifuo.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvpduilw.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtjkqbydtb.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtkofjkpno.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtdonreqit.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtkmkwvuyp.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gtuwhjgoeb.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtouiewzrw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtjamxdcdk.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtkwvgcenb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gthsdhmqje.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtcgqsoklc.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtfvxqqkxe.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gticzmbset.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtxkinunwr.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtmigvhotg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtoautdhlz.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtdxbgfrxd.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtanbvvdin.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtjwsdtugn.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtcdzstuzz.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtssfumqdr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gthgoztnfw.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gthxgrnqpi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtjzqhrbyc.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtkpbrrhfz.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtobsjzmlk.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtohnuizvl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxftntohn.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtbvwtljta.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtgnkimfuu.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtovksrcui.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtrwhxywvy.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtnnalpvyl.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtcoujtnsa.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gtkbppguch.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtudhtdrvk.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtmswustvv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtjzpnpwkw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtqjjpzhxa.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtqxrhqyns.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmtxiktuc.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtvpvlivyo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpgbbtuax.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtkgcuytye.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtnasbppwl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtvlmdlpuz.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtufitdvpp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gtayaejwik.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtemmoybrh.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtzbyahzsb.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtmkqsifnl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gtxnyvopwn.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtvwgnoapb.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtfipmfblg.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtzstimxtw.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtvtzoftqq.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtvcaumkgy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsljsdae.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtzebgynvs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtvmxgwfns.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gturowvuul.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtlifwxbbv.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtgujhuuqr.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gtmnstuhkn.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtnftahbdq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtzzzcyubk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtingwqyth.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtfeeejlqo.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtnjtzjqcb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtzgkgtkqa.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvggkqzb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtrhyazasd.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtqykafvoh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtitcougip.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtmvbmikte.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtspiqitjl.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtzbhavmns.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtdscrvaza.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gthunwqxvu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtoiocsrjm.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtvyjuleay.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtvivpudrz.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gtuemezxaz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtnpbjvium.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtklrwqalz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtpztpwlmv.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtgvzukfih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtrqmwousw.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtnmbqpded.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtnshnsdtb.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtrpufsxrk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtdemqacrl.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtbvhihntv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtqomrlapr.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtvzvmjvnj.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtspbwxvhd.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtxllqystx.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtaadmkquh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtvlnzxaiz.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtsayeltvb.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtmtsvwiat.html


<!-- 参考信息 -->