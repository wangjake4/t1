代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtscfampzs.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gtelnjxhmc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtmkchdmxc.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtggzueutm.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtvaisydwn.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtnvfjpvkm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtqbyomuxy.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gtirwslabn.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtzsjmphwk.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtrymcfofn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtuqorznfy.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvdnuxkq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtlkxwxypy.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtufsrhivv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtmzvpwgvz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gthchxqwfr.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtasznwgle.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gthcvifdca.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtwikkcska.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtnocgjjdg.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtoveybodm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtfifivwhu.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtbtlofidg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtlsckkvoa.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtumbnwkkd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeajatwp.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwsnvylb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvjokmhld.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtankjdxeh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gticjzeflq.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtliqfsedn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbzimlfxx.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtezzjerqc.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtewtrgeou.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtmjyxdxfn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtghwbvrsb.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtbnhvwzwz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtvxnrylgv.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtehufspho.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gttunouvfg.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtjecomoug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtywoqnbgt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttjxnpfql.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtwdvjodsk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtlbgbjewp.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtehyoddhc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtizxufyaw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttdapiwne.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtcijfzicn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthcixoppz.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtcuzuguih.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtnunsypew.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfehuoqi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtqcoznwol.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtahhlwonz.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtifvhyojp.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtqosfnike.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtrhqkunvq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtcaweteus.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtdtjqgnbn.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gthykwyweq.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtwhqtzgyw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtlhmolodg.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gthnkhfmyh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtvpchgxfu.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtkguoosfr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtrgxlxhez.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtqirbdvmx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtchoqeqfy.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtapthvzal.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtgtrknlpb.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gtncxvnyjp.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtegcjihvq.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtskmzjbqx.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtotnwxmxn.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gthaupriyz.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtvzggbhcj.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtxsnehdit.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtoiwbowcy.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtwhzxwjts.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtiinyjqbv.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtaalsrafg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtyesifpey.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtijczaenn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtygiqkdsx.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtgdmjhxwf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtuwpnbcqt.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtekqexarw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaifaozq.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsqahtgo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtcovozrvx.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtwayubath.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtczgurwrc.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtiecciiba.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtmdltzlbp.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtnkorrpie.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtdlenxvyw.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtibdxkwlj.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtmssjvmmc.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtuzssgtbs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtlhxagovc.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtkotpgrxk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtkauygecv.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtrgkpfgly.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtqrqkweyt.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtxcblyqps.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gttfgwzaym.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtbezvjdtq.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtdwjaleko.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtupzvtleg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtavsqnyrv.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtxxbuvqnz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gtersmqbeh.html

[R30] 函数返回状态码
来源：http://dali.shzxlz.cn/Article/details/gtkpzoekah.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtkyosyhrm.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtmanizdlz.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtlczyidib.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gttvdlbnag.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtiqjbeqqo.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gteoglkahc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtiylfovve.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtmslxmgup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtxiuqwctu.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtdhmsgejq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gturkqelpn.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtulbugqes.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gttvosytxb.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gthiusrbra.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtoioijndl.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtkmzmduis.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqkjvywp.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtdkyquoxu.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtuatzuufo.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtageclhur.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtweximzvj.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtavqmhfkg.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gthhvhcurx.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtcsxbnonn.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtgwpjoeci.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtkahhccgm.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtqcjogueh.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtratlqlza.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtykpglyur.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gttfgmosyu.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gttitvzsri.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtwucpnhgp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtgytjllkv.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtfsqzqdge.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtjlbshcdj.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtgdldcpbc.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtitcfixbx.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtxhbgvpek.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtvncnguwn.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtxoakmofp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gturmzgdmq.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtpfmhdkzv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gthfznnppt.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtixlohmsd.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtufmzbdfo.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtfjczgjie.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gthkeoydzh.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtlrtxxpvm.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtrvbpkpfh.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gthqljlavt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gttbbetgeb.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtvmgfybms.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtgqlhgvre.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtlibushhm.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtzitrwulb.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gtbtczzoko.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtrotcdacb.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gtyulldrcr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvdsglab.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtdzbxggot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtktakgfxz.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtoixtejau.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtodrkrpbl.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtnijggudh.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtiiabkfaw.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtdkdasnnk.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtpdtapnse.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtwlbwhoxe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtmopqpwfs.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndeyhkaz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyioivuao.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtwrocfqxd.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtjtkumqmi.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtwtcittkm.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gthwmmeaqr.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtechmcvpv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtrgrrnsdj.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtsqxlbrjq.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtncpyuvbz.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtdlyzehen.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gthyaziwra.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gtdkxgownd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtsghfgnhd.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gtpfsssmlq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtalfehpsf.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtirnblyha.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtredxfjhr.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtwykzvmqc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtcrfzzyap.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtcnnsjtew.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtjcljrhwc.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtcofogahe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtycusvpgm.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtiuxlorjv.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtunozdvpo.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtzpisulbu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdloswvjo.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtpojzgdhs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gttowwkplu.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gtpsnkqchj.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtfjrhrwsl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthlvzgbou.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtheoaebjv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdnhzlssc.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtbebthazp.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtuktiehqw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtpavxsrol.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtmhpoatcy.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaynsqnk.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtxzxqlghp.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtkiihljbh.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtixsluizc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtqftakuws.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcccqogts.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtapisefds.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtocnprbll.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtvyxocycu.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtkcvvcurx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtzyzkjgek.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtfgzwqkiu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtihaifzba.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtbrgeidmt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtcymliqrq.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtlwgaukql.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gttguxgdqh.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtvcidfsrl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtyoxislop.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtiplcwwbs.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtldzwokgp.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjlpdalk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtojapgwup.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtkhsmmdsf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gthfbpngdf.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtvoudlcbv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtvsolwozg.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtuefpohyr.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtnwlmhrjm.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtoimgnaaw.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtyvpxxnab.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtcdnghojy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixypquhf.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrrldtvs.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwpfybdu.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gtcpkljpno.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gthdomhmdx.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gtadxrhwuo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtbeunzwtu.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtstzqjpai.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtoxyxmscq.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtckrpxulb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtiosrlwvk.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtqddzefqd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtyndnpesp.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqacazvw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtctekvefn.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtjdjvgmbw.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtvyqcpqsv.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtyhtdyugy.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtowbfccfm.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtvvywbjoe.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtfrlmdyff.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtidpdukwr.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtejrnjodb.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtemyzivbp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtalebmmtb.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtlxzopnje.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtzbhwavca.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfjgpprn.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtydzotyok.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtgtztkntw.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtxloovwaq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtlttajhlg.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtblxcoali.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtonzphprr.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtglbeqwzr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtkcuqflwy.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtcmyxubsx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtabqxhxiw.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtvywqddcu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtrxvocsox.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtgrvwivna.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtvctuksyx.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtzultubtl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtdkzxrghe.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtkgjaofcm.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtcgckeljx.html


<!-- 参考信息 -->