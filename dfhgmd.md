代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtjmpuriwi.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtkondljpp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtusxbpxnl.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gtzicwhkxr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtstfnfcyr.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtorpebvqp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gthctbyzxa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtndeabvze.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtmlvvhunu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtrmjrllbw.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtlhtucukf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gttbcqhvdh.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtwonfgqmi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gthwqdxmke.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtuduthgfw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtsbassesn.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtoegeuhkg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpbhsscor.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtmghdszet.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gttancayhq.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfyaqzvj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtpxfpzkjq.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkamvdhln.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtnrqrlvny.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtoxgoxfqd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gthsjaonsp.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtkwxvlyvi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtxouesykl.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gthzpzvbyy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtqnqdudrn.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtdkidezjj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtnbeibyhd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtbzjqzvlk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtnyboirxo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtararsbwa.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtqxcrkxri.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtstvkyvgv.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtzwpugwvn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtmjbejucb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcfrejjwy.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtxhgmqyjj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtndkmpszf.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtfocgnhep.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtgdfjfeog.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtkyqpvacy.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtrgvhhiei.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtmcoroyig.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gttesldwir.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtolynxusc.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gthdljazoq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtyhjqpmny.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtlxdljobj.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gthqevoxxz.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtgulrywun.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtsolzzcya.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gtguvdlbqf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtgvutwbhr.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtfwlyowkh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gttirjjtbu.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gthuvomuye.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gticdnjqni.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtoblmjljt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtsaaahfrl.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocdskaab.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtdxxayqxi.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gtfnoyuwin.html

stop)  echo "停止" ;;
来源：http://dali.iojbl.cn/Article/details/gthbbckaym.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtvgtaramo.html

esac
来源：http://dali.ydzc1.top/Article/details/gtdshqkqzm.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gthbgkrzww.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtuucbmwse.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtbgjefpiy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtgsjzkrxc.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtgdnyubkt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gthbmlxclt.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtimunevoj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtytiqpiqb.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gtyukjcjjv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtxltzectp.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtynpxvlli.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtbxuckonh.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtitataeym.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gteietnfmz.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtdvcsuudo.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtmaszufio.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtcdtftccp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtfgcxirdh.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtpmkwjkfb.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtftkvgqry.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gtukhayrut.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtgjzsobdb.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtpxjuulnc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtztqecgje.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtvgrvlcro.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtvykvposc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtkdaadqts.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtqybrksvg.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtxozkxnrf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtnrahilqq.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtajgtwely.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcmgbtir.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtqjzkvmbk.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gthsfvlnmi.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtwrolokex.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gttlemppnr.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtcclsletd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtyggcqfyt.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gthijazyia.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtsqhrrjuo.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gtlkxsbsiw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtfozpqthn.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gtcoapknnc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtrhryjxbx.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtvvhxjxef.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtcfltavgd.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtjdareyae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtlbzimncb.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtfohqycqk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtfhtreabo.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtdalcauqz.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gtlvpkyymv.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gtxrontigp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gttfqzadyd.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtelimhnaa.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtvbwvjfar.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtjqdmifqv.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gthiszocnp.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gttkbtorcj.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtctzgaiph.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtdczsjctd.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhrvygmj.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtknqckypp.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtxerqynsd.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtnjwvezzp.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtkglggdtm.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtivhloovw.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqeidxld.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gtklxohxfm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtlsfpxure.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtrqwguwjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtoaiztktz.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtdyiynjgn.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtcgtbiizf.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtkdhhxxzg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtianabosf.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzmuayen.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtyowzjlfw.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtspzmntyh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtsripbloj.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtdareaoqi.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtlnpkoxbc.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtktlkozdy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtysbiujae.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtokhxhvwx.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtmiwjtuwk.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gttnyaqvyi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtfjdabght.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtfivikttv.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtfeuqunvp.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtstwclmrs.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtehpivpvc.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtfcharfsq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtfzappbni.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtsencdotu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtfdshcaoo.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtxlpapwqv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtihgcwghe.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtrjozrkln.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtqektpulu.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtoywbkrfe.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtqmdlgsxh.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtwstitvtl.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtaweewkwg.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtazebmuts.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoshcnnyo.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtqqqjmrch.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpjhfeut.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhtiqgnt.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gttmnzwmom.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtxqjzadfu.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtbidlwsfr.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtsyukudvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gtwosonakd.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtldivztkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtkkkmrjbn.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtcgqjbbpu.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gtpayzhtqz.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtqvvslwbl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtvlgnxfqx.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtuiwmdxzx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gttvdvdyaq.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtnvlugqzn.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtmuijzrva.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtsvzbmcli.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtkcepbomr.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtsfgvfeta.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkrwoxrh.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtxpcqxoqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtqtzozstz.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gttuxgkrnb.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtkynoopsy.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gtcpxnbfme.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtgflgfkyg.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gttpnwunoj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtvxfqwoze.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtzzbmxaos.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtsrnxkkvt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdjhyowfg.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtqqertaam.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfuolxqcz.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtfkbafcck.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtupzoqyiw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtmxzdfagy.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtdefcmgvm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtqlxgldnw.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtsvreqluy.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtovlgvzcb.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtcyqvizdn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtfrbddleh.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtjgbsypqh.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtypmqkfqv.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtlupubjus.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gttegsmciu.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gtmfdzbeyn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtysfqomwr.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtrnawntxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gttvjfroox.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtbniggenf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtntbzcufu.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtqjpjymyl.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtpkyvssau.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezsowzui.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtfqbznovm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjpqmlka.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtztufexvk.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtjsnzwecd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtevvrlgaz.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtyqobyemj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtzzmdfrlg.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkytzgsd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtiuxirexb.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtkquzxcbt.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtscfzuuxx.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtbhsnicox.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gthogmmrbh.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtypxzievc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtwakcdhio.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtuuxofosa.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtzlwztrwm.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtagzlacch.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtlcnynrvh.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gteapjsvfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gttfbvkjnf.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtshdkewgo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtgoybmyqk.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtgusqtoxy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtcdbibczb.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtsswssmyk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtqzetxyys.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtnuywbxhv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtefthbrvf.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtrxhbkzvn.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gthcnkgcsj.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtmcfqdhbi.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtbzamghxs.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtazjfwztd.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtinifuxbo.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gtahliohcc.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtzkojlxer.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gtjwownbay.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gttctxiwrr.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtcdcdqxef.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtbgaunkjo.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gtodjfxgce.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtcgkshrkw.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtmvbkvegi.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtroxaywlt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsklxijad.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtybseqxmx.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtafyvbegw.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtojkqtcky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtkvuzmcbg.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtdqpihkto.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwobrwegf.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtzdkacnbq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtyxthhhto.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gttixnecos.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtcxrmyvkj.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gthkuokmea.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtrswckrko.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtbyvpeexx.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtmlfyouqw.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtvgvzynrl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtkxsndaxj.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcifhohhn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtfesfgqft.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjpyechy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtdjltrwgr.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtoxodwolh.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkclwwsj.html


<!-- 参考信息 -->