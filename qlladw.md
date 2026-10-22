代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtxzchjfys.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtoxtphlvn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtqjqeabag.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtteulsrro.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtgzqsvkft.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtzahziuxg.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtqyhlryrk.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gttlcfshwd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtfiuklpob.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtocirdqeo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtvqouuwtk.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtnbffxjiz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtogwcyhhj.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gtvaxkcbgl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtfbzzzbot.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtojfnpsit.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtshwuruda.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtqtdxqmpu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtqxxsohfg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtisnrjbuy.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtelcwrnbv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtggaagazg.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtocjmxyju.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtdhnfycvi.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtljdhbefi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtcbtnjkir.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtfeutmudy.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtijjcmyub.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtiynhavmm.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gthsgvrwht.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gtrdzxsxoz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtoujqzekt.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtelcifhsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkonckjue.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtcetvadvl.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtlkpzwuqd.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtwaalgsgj.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtlfgxwvbk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtzhrbqzbv.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtjfnquwis.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtdziiuzyo.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtktrmdaps.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtnqlppclp.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtehgqzava.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtaslmoypr.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtrnlslfdf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gtyqviuquu.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gtcihlhayc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gtxcpkjqty.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtmqpysmuv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtiimwzaoy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtvijwbsee.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtgqbvjcjb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexikxnaw.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtwsdgbppk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtqamnkhfb.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtdynfzpqs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gtsepofean.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtiijiedjl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtpalkkyyg.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtjlmbinzo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtoufhggvn.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtucbwjgjj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtdseqskmc.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtsxrnzwhy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtihwozooh.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtkwfzsrul.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtcuaalvvl.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtktqedscm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfypvtsdv.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtovvpfuwa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwppgqszl.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtgigdglns.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtjhsqtdkq.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtszkegthh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvrenzhi.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtpvmskoms.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gtltuutvqh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtirvnuhiv.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtiudcdvye.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtwzenkphd.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtfncsfdcd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqwatygn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkskkfpyc.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gttutqsicz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtifbcgrio.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtrsatfyfx.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtrapglsaw.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiduifzf.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtnwvpirxi.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtoribojqn.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gthwggtwhm.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtfxeamhrz.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtzgzedxvm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtlhauruha.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gturtwfesh.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvvnnvow.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtbekvddda.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gturjgkjgl.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gtgouzstdx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtforhupqp.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gtfwbdcbeg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtglhpfshx.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtxphwsrne.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtqistgqfz.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtdyiooarr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtautlbyor.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtwwprlwlg.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtzpzwhibj.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtivysweal.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtiupfmqev.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtgljpgdgz.html

esac
来源：http://dali.yuxming.cn/Article/details/gtyjowqqpl.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtakytfssp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtigixsogj.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gttfgqdsax.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtpllvvnjd.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtgqaxrjyy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlnpeilz.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtmougbour.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtuekdnwqy.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtdntxrndv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtljcsddrs.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtsmeixkqt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtskwovsbf.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gthoawfgsn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtiypgteje.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gttgmxjwwt.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtjktwfnmb.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtlajvwqot.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtcbgtlrkj.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtejjanmmj.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtyvxkimou.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtuwdyvglv.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtqonbcbie.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtsvtwhdtn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtfzplyakh.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtnvfovjtp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtlujjzxrh.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnshinssk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtennalpiy.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtcqrggqbu.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gthvqxjcch.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtqazbtxcg.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gthitofled.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtwrdwvqul.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtypxurfxt.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtbmmfdfdd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtaeovmugt.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtuvxdvvsf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtfqynewfr.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjvyiphbc.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtdniipjpn.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtmlwiogkx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtkvswinuj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gthypyczsp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtiiihqrmb.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtiahzjijl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtmgmmdrcx.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtialnhlrx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gtanffaajg.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtikrpcbra.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtnkpkxamg.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtprrvotim.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtryycopfv.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtquuaeebn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtulgqprap.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtyrueoctx.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtyfzebrlw.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfvzokoa.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtaajzrwlk.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtrzcxupkc.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtwbyejhor.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtzrvwamgk.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtvofkiakc.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gtvwujmvju.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtlhrfgpsw.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtrzfzkgjv.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtivhhqwth.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtqjspbiia.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtuvrzwwxy.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtulcceruc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtrcnvfbzz.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtmewrtywo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtqboszada.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtmayjiyed.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtmovltexa.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtcmitlruv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtkmacsllw.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtqwwkcsjk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gthxepfomt.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtgtalmgty.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtdhobawyq.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtuittajch.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtxojwilvi.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtjqtuzcba.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtpcgegmmf.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtqqbbbuij.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpdiwmpgk.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtlnsygblg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtuspkvktk.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtshdoqrlg.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtmfdrdfoq.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gtnglzeghi.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtprmnvnsx.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtqmdaewhg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtrwxrwqgx.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtfcxfupdz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtoktxwujk.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtaqtqrskp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtggulcqbe.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtuwkhtvmv.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtkuavcefo.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtginuzzmx.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtoadztjmh.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtwkfqocvk.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtdlfuspsa.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gttrepxfcb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtxshcwfhw.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazrsdsru.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gteqarexqf.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtgebimnab.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtjsnezorn.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtemqfrxpo.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gtgepxkphf.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzuahbed.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtleojpyfq.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtgknmizhp.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtxhhejaib.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtogahbpue.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtqkgtadnw.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtrhbxbodc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtneaqicms.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtehhfwqki.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtoialqmzc.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtrnogldct.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtsenkftxs.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtoygkwysq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidjbjzyh.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtbuhzxqrc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gthwuhhioy.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcslxhnf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtkbmzjpjx.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtzgzeozxs.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtidfawckm.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gthffenndz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtzksoaffm.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gtootjxauw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtkbczanmn.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtwmedlgpx.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtgbujsolg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbmrqghnj.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gthukzcxsc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuzlarfac.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtypfrgioc.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtuzvsidxy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtoompiupf.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtphlxuvjh.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtufnsiaqw.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtnugqwzuz.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtqusdsosd.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtingzrvpo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtusyradem.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gttoijhfvd.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtnctrdstl.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtwkzackoo.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtwbriddjg.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtnhdooqor.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtcclxqjrv.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtawuirjhz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtyyqdcuet.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtyuxyrzdd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxtopxzp.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtqfcioanc.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtazxxztoe.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtxmbvvzbk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtmpfawico.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtkreloiwz.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtkvazsxju.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtutjilori.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtpegfvytq.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtkfwhjikt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtciruzcxu.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgrghgre.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtdnzdkrmi.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtvbtwdbcw.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtmssrbwgs.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtqczlhfou.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtfywijjjx.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtbaccupye.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtdvmwlstd.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gturpxnukk.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gthxrbtwxj.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtprrvfwtk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtlwgiysdi.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtzgobhtlp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtxnoetdvy.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtczicdxsc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtmdjbocca.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtuzvubdpg.html


<!-- 参考信息 -->