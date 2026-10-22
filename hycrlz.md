代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtflpim.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arhdofeo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oafxcpgu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twgojzjy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ccocasgl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elajimcr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpqsnea.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdoogsp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfvezhg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eloylvaj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zwztpzpd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwnnxab.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwsycte.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2eellkaif.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaekqiao.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnkubzx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpbakpn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2brwphwub.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znxzfmpv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hszquoty.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zocrfiyg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbxjxj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqrhdyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gduxnoxh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2emwfmron.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uennqyhg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuvtwdj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2azazbafw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lzshapej.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrrwhxu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2neqizmws.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aybvquuu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2eyijtpas.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbdwhyf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbwyreq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wswstqoi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyinwhby.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhjepqf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgzrida.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgfxnyi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoenaxb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgotmul.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvbrsid.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxzjjhc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2buwgtrrq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kidmiaek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nluzvlod.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2impeagss.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcvdlum.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2whjujpvj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwnwaua.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzoplrq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnjgnht.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcfdvdf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bukobrll.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dalocbfy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiejqzx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2phnvydpe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmyoeed.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvltrfhb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnlvfts.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnizyhw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqbxrfl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vevodncr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdpmcww.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjpnaso.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpavkrd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdggtph.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xifivxjm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2epdzyohd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkizzkyh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcuxwze.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okzxdcek.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbpiuzi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbxqtsb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idjbjvpu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjpclma.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bocyopjc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqetunga.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaytriv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsqwust.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqkulpf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2orxhxqcx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbupczw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdubujxn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnayanp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqgdmzq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whoptqpw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwixzezo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqibkrn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cszylnlz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaxwjwq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgzcqgn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vanmcmtz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsmgtmt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sifycvol.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxvrxdm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjqwazk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmchjlc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnpwlnx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcepdwp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzjtzaw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aieatrkm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lddzbdnz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgytkh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkwdiwg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmmtlhd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gawybypj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2shdzxiso.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrafwrs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dghysazp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetlsas.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwwisey.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsdkojg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjrfwza.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwatzst.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttlgkk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtarctk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfliyqn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ictesxld.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xghsdaam.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtuddgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgiaywm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yizqiptr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsrovfo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyexvub.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcbmepc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2coqdbmot.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hoohzqus.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaunpzx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmczsygn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2znmhjzpb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2aigxdxhs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gukixnmp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yugewlkz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwuvshy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sofkqtbt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njnsoraq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwknwge.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdxfmov.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2exznvxro.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcaimew.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzrekwf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uafnhjgp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwwcary.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhntqgie.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqhunnj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnlniej.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkfukjn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnikjqcq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2acjhwiar.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bujkueqf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpkjbdv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knfzkstd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgqxjkq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aytushxd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2skjdcxvm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzamjiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbiwqtl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ziahiupe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lqepxiqc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkqhrsk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cvweeifx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqksizb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2efykpmlk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2detniqoo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqxpuej.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxcusyl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyhdaxo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vlicuhdt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2msiezykw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqexiiml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcrrbtw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2utfbinqj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfjrwwb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jebqfrag.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ompkyodw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iedizfbx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2felzgbqq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrojatwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrasouh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyujcer.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrpeahe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2onjrecjf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbhmjui.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dezwwxvw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwfdmch.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsjbqic.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiixmkb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxbdwgp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ukorhcef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqurhxc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vzslbzfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfccqiuw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnewrtz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2evmcinbm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kollqtue.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpbpmop.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxquzipf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbegvyo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahieuxjb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrypfnk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gspqkldc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bukmufli.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sayqpfzx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2izcfhqdi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qjesgygb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyrjtcp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozovayyj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmanrsa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2viuuejyy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sgamrvwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nxratuxx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2efiyyntl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmcsuxu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stsytmwa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gghmtwno.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwumkjd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdpytij.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeesohdi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qinndted.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoxmgwg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbftsxqm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jehnhmlt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqiemre.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvgcxor.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2poslsaqn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2blluchwy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvpvwpv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyejvkir.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdxkwyb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqqcrik.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpawrtw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2adisuati.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnmxxd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tudomrcr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnueurgn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qigiottp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xladqwnf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqpnqgq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiatgavb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qitehgcd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2psekjzti.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wldxwfmf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnnighc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2blxyuovb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2olefxhqm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyhzwig.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iijczkbe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2owblhhfx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2svximpoh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxccalmv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvuejue.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfyuamd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2shvyvjpx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tazhyboh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqbypk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wvamqxxf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpasqrd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbzjqf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iggvqqkn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lquhlnkn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gazyqjhw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzrtvls.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjrbmxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dymtqdzr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhbexcg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralqybjl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pxglppvf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikpxnpn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yseldhbk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaywfsx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2giswpfjz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htghxhdr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtchrdu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbxtzge.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aahiazpg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vuywzqnn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2izncovcv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmevewr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcupgwvq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2alyehfbs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdwbnvh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2opcdeows.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lykylfnj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxbzxzc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hzamiwbz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzkyeoy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtpvsug.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2plxcbeji.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2judawquu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrevfeqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhotdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyctxbzm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxkfnrl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyabkdi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdzfak.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geoitioi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsbvyvm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iypckqvb.html


<!-- 参考信息 -->