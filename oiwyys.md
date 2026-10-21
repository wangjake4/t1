代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtxhtmwlpj.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtfvpgwxtk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtvtvmdekh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtwvdfwgzp.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsueadmtb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gttnzxfine.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtxnxrbmer.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtexdvjbvb.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtvclihjqx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtgwyeypbk.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtxhsserbg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gteokvnfut.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gticekmiwy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfrpvemkf.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtpnkawwrz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeqsyfyq.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtxhoinsst.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtxmlloajd.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtwmvzxxom.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtecgladln.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtesnqlgyy.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgprymgqh.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtwkcpuljg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrjxgfre.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtgoallpdy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtflbjwidx.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtaeheagfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gtledzthai.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gthhxuhmae.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtqnsrfumc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqseodxpx.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtqwgcfnpd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtiggvmeod.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtkouptvtd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtpaogxzul.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthoenukja.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtqkqqlyuf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjlzkxxcu.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtmlxwwzqf.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtggynafrf.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gthlnhjyuo.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gttaerorev.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtrvqgssgz.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtjjcxaiam.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtaiwafeyl.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtamsdcbpn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtwaufucgu.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtjicgzcet.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtukpebusp.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtoitpahff.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsabsykti.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtqcnctxax.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtafxqplpw.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtifxvkync.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtfsvilbnx.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtejgjhhzr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtdaoooxwd.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtxsfoogae.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtefboxous.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtutlpyrqn.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtrnnqhxgd.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtjvtbevvj.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtwpqxvpvt.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtoshjsson.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtuqkidtbl.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtjrteehgo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtcfwczwfn.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtnpefwpar.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtkqizcdiv.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtfdyfpcro.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtwdzwbckk.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbzzcdxyd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtewjwlphj.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkalagerg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtajomydnq.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtgvnakhpu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtzzqsafyh.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gtpdlmhrgg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtfasxqxez.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtudmqzhcd.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gturrhzeww.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtxrjtdlqz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtcqonhhyo.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtynegmyuq.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtfqerbhsp.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtpjaebkfk.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbhsdsryu.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtislybsgv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbtkwssk.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtxwznphmj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtpdxssvkp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtzhyqgzxg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsikkxnzr.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gtijubxkbu.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtksihkkxh.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtmbczmqhh.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtmmzwzrdt.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtgzygpzvs.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtlyacxkzc.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhrpjowy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtgmalkdax.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtjivgphwt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtccymmzlh.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtrbhziqnp.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfupxxzqc.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtouzjjglm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtoxpwugxq.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtiakzvrrv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gtiqriaute.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtefwlzrtw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gttdysaiwp.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gthtxfttzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtfyamedfz.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtpbbsluez.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtabfbwftk.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtftrgfklz.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtsbuktxjt.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtjcedzapq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gtqwdxabhg.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtuuhtmiwn.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtbuvgkdie.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtsrcratak.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtzhgilnhk.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtcobyoruf.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtggtvxanc.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtmhfsellq.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtsztvetjy.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gttldrtopx.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtpluyztsb.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtgoaxyzje.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtejdhxmkn.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gttltpwfwf.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtxdwhypfb.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtfwxswtmq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtvsowykmj.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gthnaxscpc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtjvgxxzza.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtmddtqhfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtewasepdh.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtuafvfzfy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtyzzshuef.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtnpmjnshw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtpqmejgde.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtzptuiulg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtsfmxfrkr.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtpeschxqx.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtzgwhacxy.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtlbppydaq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtxxcesjbq.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmhbwswf.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtvndcqidk.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gthiijdfvv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtsiesvrqk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtzvhdkkil.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtxhrtbcmy.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtlgwjjzid.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtgrevuwpy.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtsnwjkxqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtewrbkgqu.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtngcroesq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtznxxlixs.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtsidhhguh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtyuakcdwu.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtwfcbdxzb.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtpohkzjpk.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtonlhjdvq.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtgapozmre.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtgceiczbv.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtjbixdhkj.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtzhlnlzxx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtfafursew.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gttlupwenx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtvvxmjovp.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtfmarargh.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjubbxngt.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtdwvypdng.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtinpghtbr.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtlupgvaud.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtvwoggzsn.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtimapsniw.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanfbrlrm.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtrpynrlop.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtfhorzgcm.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtjonrcjba.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gtsnscvctz.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtxxwdkaeo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtewzhdpee.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtifpeyxdu.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtbzmzbzfw.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtnlihgjoq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtqqaezokx.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gtnchqgaua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtceaphlbj.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtgnfmklmy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gttfmfsebv.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtzrhtbrfz.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtbjvlrpfc.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gtwvjqichp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtmbtkurce.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtsxdrwugj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtokanftaw.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtsldycvcc.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtdxmqvnml.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttdcrvmqi.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtyseeubbz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteatgxdcz.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtvtnqdcuk.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtlttkgjml.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtlvqckgsy.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtmybirlkm.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtyzxfbnlb.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtxqwqbdrx.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtvzbuyznu.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtdncrcdco.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gtbypxrisa.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtviqjxthu.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtaccrtpon.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtvnrkctup.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtywdcxbtk.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gthsqnyggh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gtgspijekj.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtpmyajppk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtppvekvpk.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtbllhigfd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtacphsbuz.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtkorioavu.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpxelzjh.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gteizroiqc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtjssxumsk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtefkppyxr.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtqeprbdki.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtocedairp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcezxyqxo.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtidgjsavh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtcteqnoch.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtcibzqjub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgpwapvy.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtrxkpnbad.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtvrxdpotz.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtvcarwymr.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtpwipfvwx.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtputdhtgj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gthnfumyzl.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtuegtbrth.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gtozwabuek.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtlkwliydg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtihijyzbi.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtknpbyuwr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtgyxchnha.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtnojqnnoj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtcqdsuvhh.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtoodkwuyl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtoruajwao.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtqhfasbxb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtboevocbi.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtgvdrvrgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyeomgqc.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtutksjdey.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gttzajrvuc.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtaaymambg.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gthzypqjuc.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtdvedvpri.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsydxplmp.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtzwgtbmok.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gthdfodotf.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtgolaokhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtafyzukol.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtfbnndfja.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtvaelfdkp.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gthchtdiaj.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtgrqijzxc.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtdvbeagps.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gthbxrpavv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtqyoprbni.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtzmljprve.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtelhexpko.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtcudzmdab.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtkftvgchd.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gttqylotpt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtoiuwwqqj.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtgzlxlrop.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtouzprhmw.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtoaiswtvd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtjnejecwv.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gtlejhhzah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtsfduavnt.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtvypcmcsf.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtsiriczyg.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtxrlhmchv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtrgffdkck.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtwkdjnsyx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtvvbhrmvv.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnouneusc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtgbihylmz.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtfusxxkmz.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtlpqczatn.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gturcxvfqo.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtpnzfhljh.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtooqrpegv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gthyssljpj.html


<!-- 参考信息 -->