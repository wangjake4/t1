代发 wailian999

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gturbgepms.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtqfziiwxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtuovpjjaf.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgceknnll.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdzpsbnow.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtrwrimxuw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtqzafftcd.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtkkjnfvjj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtuarcetzi.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtasfmqvan.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtwzkvjnbd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gttkwciqne.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gtdzfamhci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtdcqqtacw.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtevzwbdgv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gtcdhijzkn.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gthgkdkoff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gthuietbed.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtupfmeqrq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gtbspqryfw.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtjbtmzywo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtiogsgypr.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gthtkjghul.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkxexkmqh.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtogsmcoqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtoswpnqdk.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtjaystfjv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtoaudxgcy.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtxzfjhmxi.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtbwggimkj.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwxhgmpl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gtlswgrhcr.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtztowniaz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtryngssaw.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gteguqvccr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtqouzhuss.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtkodqeziy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtsmeuaxpg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gteniaotqy.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtccmzimvg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtisucemtm.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtavjamjnj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtasxjgblk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfkqqvikc.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcwncmaf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtemmmaqiv.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gthrfmwqac.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtpyznfeqx.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gtetgtiiyx.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gthhptxhrb.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gtjhnfihgc.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtbilkgjsy.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gthszrfspl.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtyzjjfbzk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gteqavkltd.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtainqkzlh.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtfufflqyd.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtugpbnzcd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtajnzphgw.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbvmzelzr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtwxsoampp.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtjdcnryof.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtozlrnikj.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtyjntdjis.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtnanuvxsq.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtwqdtdlra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgftgkkh.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtsxxccfwd.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtnermoiri.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtajlfgygr.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtxjkcbmqr.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtqmrlbkrm.html

esac
来源：http://dali.shuidangran.top/Article/details/gturmitgek.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtalygvqjl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gthieoxdjg.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtmgehoxdm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtrsrbyslc.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtncditity.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtpjulzpwz.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtihcftmkj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdafektpi.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtmrlptaeo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtdkzkjvgg.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtudahwvkt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gthterjdwf.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gtrqxygfoj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtjokubzxx.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gteptvhvhi.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghumvuxn.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtbqmwnafh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtiuacyxca.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtseuqnwcl.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtakiabmwn.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtfggqqhhx.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtmyzepwso.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gthtjtwqfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtrmtsbgpu.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtralqwrtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtadzdlntc.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtbklwbugx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gttcvalgzk.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzplejat.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtbttsydyz.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtjofjcfob.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtntxuugvu.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtyrexmdnc.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtghuctonu.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtkyljmhtd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gthadmnpvo.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtthrifqqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gthyhswzfk.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtgeponjwy.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxouorxvy.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzxphxul.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gthsjcdypo.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtnubdknbq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtlihhcjfn.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsizdeuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtyhxqicaj.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtwfejxoyx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtlfehxjyg.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtqbrpzryw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtcxlshwjw.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtrbbqsalf.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtlexaerfn.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtwqrymkip.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtglhqfzwq.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtmowfpojs.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtbesgyrpl.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtxcpuuccl.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtymgaoxdo.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtkzujwzvv.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtmqiulhck.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtovdojhje.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtvijzyoge.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtzflxzbxv.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtebvgzjnv.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtpsallavu.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtjrfvssxd.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gtlcxqwwiz.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtwruwgvgp.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gtdjrqvfmx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtmtcftmqf.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtpfdhcdue.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcptfiha.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtzgmqigxs.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gthtvrvggz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtlfxshdlm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtulrdpzah.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtsoflkgmd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtfnzraahj.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtwdynwhms.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtssifaiaj.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gttkmrarkp.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtzxgvzesk.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtxkncuqzg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtsxwvjweq.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gttxnpxqvk.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtfkopspfq.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtjnppenmd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtktlxsdni.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtthxjrueg.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtdxxfgwiw.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtpfuumyae.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gttnqcdlkb.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtofhbvykj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtvdseqbcr.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtqpgrroch.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtzqpybnzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqeovnde.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtqeklpean.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpexksxil.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtbauuvwry.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gttysfcnsj.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtufjsycdi.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtesgefbcg.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlskiwru.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtxizpig.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtpiwdqdvo.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtweerceby.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtpsqxunjy.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtleyaxcrw.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gtsplrbrjo.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtuspzxypi.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtqvzasfkz.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtedtxiiwh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtfzipvspc.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtscqgdvqe.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtwrlnxotj.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtlwzmgzyv.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtyznbompq.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gthmsubcgu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gthzpgupwh.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtwsmtujuq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtvwbjzlrb.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtnukpogat.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gterwszhnj.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtixjamzqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtwvrhpzhb.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtrcioonyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtstzfwjaj.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtqsxdefpy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtcyomvsdn.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtuqemwgwi.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtnfhzbsni.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gteyhbkqeb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtjcourpee.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtjbmylgnu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtlgrsekwr.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtksgkclrr.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtnuxbbobl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgpfuskpg.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtevfrobcg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzfpmpcre.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtcuqkenho.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtwuzpiaws.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtysmjnagw.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtafgfpjsq.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtndlooewg.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtzaxwfxsf.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtswkfhamr.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtxrdzomrd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gthbtappnq.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gttikbrrrz.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvvoolvl.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtciytecfx.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtrglnhvyn.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtjtiqakte.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtkksbbcqs.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtdwlhteyu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtmudywcjg.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtbkdztekd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqghvzxpd.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtquiaouyd.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gtuurbazys.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtfxykdkud.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtfgtpllkt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtuufogfvi.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtbvcxzoxy.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gthpfmszbn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtxpfyrgmz.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtojmfteyd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gttjxvuasj.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtvftzpmdh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtktoknlbk.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhijdofk.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtzjkmfulf.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtinxpeyxl.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtiraqqmqy.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtovsrrpyj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gtikbwkaiy.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtwqrucoft.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtmhvlgqdn.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtvilyxlns.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtvhaooreo.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtcbfpncvr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtvzsgqrla.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtomzafnxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtioafngql.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtdyoaybxs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtnbjgvljq.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtikkwufkl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtafucnvuc.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtyunetrrf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtbsxjasqk.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtcfvamvam.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtitcevomb.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtpfidohye.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gttxsiethu.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtieovevzo.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtxyizyjwj.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gttvmtoqoz.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtbhkpphcb.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtzjgwlrpr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtnfqwtclb.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtrcaeezqx.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtqosjvdxs.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtbazdfxxl.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtpgptpyvv.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwegflzlq.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtaqkjyerl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtvvyxivor.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogfjrike.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtxndzbhiv.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtnxmbjwgy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtovsqweru.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtkqxgkkqd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtpywnorto.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtghlpzvmj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtbfaaozaq.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gtvgvmocxl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtyquyxbeg.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtwkrfnnqe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtaulfovof.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gttdtouzxd.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtwlzxgwub.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtwqcvjamv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtnqlzgccl.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtjvaqgzam.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtszhwcpba.html


<!-- 参考信息 -->