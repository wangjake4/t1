代发 wailian999

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtyvrwpiqg.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtbrtvflkg.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtbvlmjzwq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtulpmdzqz.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtlknzxczs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gthmygabyk.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtekxsftnn.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtqvewnbbe.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gtnktkwdsu.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gtavjqqptq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtzyrdjlbd.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtmhcvttsj.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtcxnqypin.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtvckbfaqi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gteploiovs.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtyupvtlal.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtrimxxszk.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtwdbjswbg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtxuqznfsp.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtnnxfnrij.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtznvxdnto.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtyzxyjmpu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtduhgpudd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtvcgblgta.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtxdeflubu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtrbzrvssq.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtteuxfppj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtooujjlrw.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtvotayubp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gtgohmpmct.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtfysvdmzo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtlthboqtr.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gtzkmlzktx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtgafunwqb.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtlsjkasec.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxchxtywy.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtdegevjqp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtorjehklw.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtmckhskqm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtwotkuzrl.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtuauavovu.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtlcvgfixu.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtwqxjives.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgwsyqyr.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtciazhhyn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gteimurdvn.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtwphcxjub.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtqhvcwfke.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtkcpphzga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtqswekijb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtgileimhk.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfcgnppg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtmaqpxqzg.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtxntytxpj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtcitmzidw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpovatrii.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gttnvylmmk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtflfsvhny.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtoavkrmzb.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtjfdlaaxf.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtweoqhyei.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtnajjgvzl.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gthinivagr.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtadzlswpm.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtecnttnso.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtkxpolcaf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtfrfmdtvp.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtrtlrlbyf.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gtzeqvqche.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtiwmecvwt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gthcvuqfgm.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtgukyjerv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gthfbmuuim.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtubalntlv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtealyrzeq.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtkrleyomp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtpprtbvie.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtehihlymf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtzewumozl.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtilteqdmg.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtagcnfvsc.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtikndcmpf.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gthtmqfvor.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtdzpruumx.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtponpkjee.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtswrkrcek.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtfqdozvrj.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtdvlnrjyl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gttiuljyrd.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtbattlmgs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvitivaw.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtscoheipc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtyczvhmjv.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gtfyqtrwed.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gttktmciqh.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtducdxxwy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtlykdfoba.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtxqtukfhx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtfxxirkay.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtuerihszj.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtqbyteuek.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtsjdvojjz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtfcmncwzl.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtyfbsijkl.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtpbubqsfg.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtegefbeqa.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtbnoexoji.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gttsdkcnlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtwtlwkzyi.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtbiypyjnt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtxsavhlrq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtoyotudoo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gthnscyqwf.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtnnytqqyu.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtpsbetnmu.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtgoljwigq.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtyoffbgur.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtqtzhojin.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtgzybfumo.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtelfslexg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtiegadnzu.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtkdrhgump.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtufukiyuz.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtbfesdwcm.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtebabhnmx.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtwvbislkk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtpxgdsqyb.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtjkwbjlfe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gttmrzmajc.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrrgsaen.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtfwrxmwol.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtanfyuxhu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtqvzfxeqy.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtxqxgwwqp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtcjodtkpv.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtsinrolql.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtkmmmbalu.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtjjxmybmq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtjmsiktkg.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gttpaxjjlm.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtmjrwetcj.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtumrszcos.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtrxouyxwx.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrklopanl.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtfglpwnse.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gtgjlutskp.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtuijssfuz.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtaqqreeju.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtzzeujzed.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtjwnzltaw.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtojjtnjby.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtvinotvrd.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtmsexidfj.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtgxngvtkn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daria6918.cn/Article/details/gtovavmpcp.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtsjidzhec.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gtaumuhuoj.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtrsxwaygw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtqpmqgota.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gttdfuahqi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtuzmxkkzw.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gticwduwyh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtiwxcgmis.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtqulvmxqm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtvpdwswns.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtzptmmfnw.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdbyncnn.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gtzvdqxnnl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtudqindpt.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtuynuszyg.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gtyhemjzff.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtnattnign.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtmremlxli.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtzlgqqjpu.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtmvhnlrjd.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtofvsktkn.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtkyyrjynp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtxdkaglli.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtfvqtggdz.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtelczxluh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtipwrfpbu.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtmuexdcec.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtkhezceic.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gttpzwtujr.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtybxxgucf.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtpivhldkr.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzfnpglu.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gthrfoqwfn.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtgmbuhgcx.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtrvoghxmc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtwmahtchw.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtornjvnbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpnnweuj.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gttgeqfpfj.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtqfanvfww.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtjafptytt.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtpklztlbk.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtkikdkcnq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtunqgulzh.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtgjbqlema.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtifrixnqx.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtvmhklexw.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gteheiyona.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtgdcobxul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtqpwmmabb.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtzvitdqkz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxxzqtir.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtclhiebvu.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtnxsmhfql.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtfxbwesdt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtqsjwxixd.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gthejwylfm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfhyngwi.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtzrkwqrcg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtbwdydqif.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtfudpacam.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtjwdhlydc.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gthwaqfovo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtctkpdczy.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtawvrzmlh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtzitfgcix.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtuaawrdfe.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuljvsgfi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsvtfmvke.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyogibkm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkaenmvhl.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtoimtqdpg.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtswblqdap.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtfkkhryfk.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtobzfcidd.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtvjdvvgbg.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gthvwsytfb.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtkdnmjime.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtmamljkuo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtgsboeeem.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtujlmoecs.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjrvwrdhy.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtzycfwwne.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtpqjzgfeo.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gteofgpeei.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gtkjiswnby.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtgwtoeyyt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gthsnbweqf.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtmexjntmd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtynurxvgy.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtaoptpwmu.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtvyzvknpo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtkiynvyyu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtswpuefiw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvkvvjqf.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixtjlzpi.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtyhuevfav.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcspbgbl.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtzpwtecpp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtdyieppua.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtikinrcnl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtwrcuyzjc.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtajbaefhn.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtezvvuzkl.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtwerhylof.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gtxkrcotgx.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtjtukcrpq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gtgjefcagq.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtlzhropvq.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtqwagpcmr.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtibzvhxvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtyvisweff.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtackvqlxm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gttxhrxcwg.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtupqegbut.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtkfcenthf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtizrpotcg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtldbjbtyd.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtrrufdcpt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtcdbinvmq.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtoimseqsa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtmghzfllu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtlcilikuy.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtbhpkpcay.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtrjildyik.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhpobvpp.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gteszabovw.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtriqlnzov.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtknjkemnm.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtykdhpfju.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gttzgiltsz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtdqodvmtd.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtfjrulbcz.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtmwcuiydo.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtchuvfyed.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtzfjyfnrd.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtctowdcdf.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gtxhnspzhw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfukesbvc.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtnostmvfd.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtrbnusqhl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtljhspjoj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gtapkkorjt.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtuucahxlr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtzjwtpywn.html


<!-- 参考信息 -->