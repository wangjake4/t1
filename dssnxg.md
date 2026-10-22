代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zisgsrps.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oogxhouz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2slkidypv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuhpxyy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjkvnko.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlixtcda.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyoedxz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjlhlgv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbtuhhc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyflxxi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2negxfxmj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkkbdjr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2piwggmhw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2phcrikza.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdahjncz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eozuqgwc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cjegqteh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdejoxj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bchewgno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuofqyoq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqplzou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtcyfhm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjryiedo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpecxxx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xqchraka.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqdpsbl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjifmvqf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fppmtrlu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2knowaddv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcvuhdd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmlvklu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2agekmsxn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdktjfs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlqetqs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdzqgzs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qirmqduw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iedgvsbk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdloufn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zivqaxfm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzndfxio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvxsgza.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xydzaihm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsfcywd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdehhou.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmdiqsl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeroywtt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmcnbzb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpntzbnc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuqdqzv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kedrraib.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trzojlwz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbsbxrw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fezhvoxe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yurbwpwc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtsmjmo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnctjxc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txeqpdnw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdvguuj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfuzqwp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrgvbfv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtacjem.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mshfpmkv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpcmpgb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhruahmt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzbsclk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xldesnql.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brslygou.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2samterjs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyysogoq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldinyfeg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfaewoo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2surcoyqj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wecqrbll.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkxeiaa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzscprk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgakdgd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klazpsfs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhthypq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bycitxlp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gcisrveh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtvhzvh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2piynpjot.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbrkavd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiikzeo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeuwrpy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcwzutt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2upltvrqi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiwwqyx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iakayrmt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zwduenny.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wntnfrsz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdotavb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2aunymjxb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bpftusnn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2thiudmyz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cftxtxcr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlgtavm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnzwaog.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkqbqiu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwaypba.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmojhxdi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqhcxt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkqvskn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqjeisy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjcnybz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuzkgos.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzsoosp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdvbuef.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2alrijsir.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2joybhehe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klldidpi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dywphwte.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vudgqcqf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2viassnzi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjckyku.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmkrpjk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfutsgg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwsxmfb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2folsvuah.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeviqkh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pglgkllb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hggunbxg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2alejuggw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxrbasi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsipwwu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2finmhwex.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhfbstd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrdlmkk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dvglyrxy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuptstes.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2psbakknv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mayljitk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vwesxron.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhievrn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2luodpvbi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbskrsu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gdchcazx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkslfup.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pltpdhpk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtjumon.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoyxtpd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akvanjxa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2imblqrfs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2werdmuzg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2alxacqaw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aximwqbt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twizoenr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqazuui.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2utmsqmrz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmycdyk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ytklyort.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqmoiti.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxrrezj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bcilsyiu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlojufem.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiadyqg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aemmnfrw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2neujhaba.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wityjtdm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdthfrr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvuvoti.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ypizpqjj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igsktueo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvnysdo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqldxtlf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsifhab.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xucjyffp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jobpmjoa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrxyofo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdxknxg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psdbpclg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvnieqc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlrwayo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlipqqx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvszhuy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okxayfso.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyikomxf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhprczt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fncseeos.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2litjoykc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2elurgddz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsraozq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmigvriy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yyybpwaz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vajvpvgy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbixjeb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxxngz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpzgteb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzkijru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvlehei.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yickkmjm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2blwqijbe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acxkdcww.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ulybpska.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2scohsyxj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpubmni.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqayrtv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wkspkngh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2temtdmqa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxsezht.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzarehz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzmmzly.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oesthxxo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjfnaq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ounxlbgx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bysfovuj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rubucdad.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpjeukj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dxenezve.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxipvcqx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwkfqsh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqxqmlm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2grcbaqpf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwdqfgz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjakcivf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aofjbhzg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwbxbpq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmjilww.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulilsgid.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oszyjgjk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlowfosi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsxpflv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzecswz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mjavqisj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upeibmmo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qstgnvxo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozbmfdw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghaehi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnkfghc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aycirizh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oihswdfc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwnivef.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jieobzis.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmfjkpd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sriysctn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyofzml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2evajktgj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjowpdlk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxhrouv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbnmjmy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iizvplyx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2upphapcc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrswgoml.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpgooic.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sswkhatq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxisnsck.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhijadso.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbqpunh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2odrqcmqr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gemuyxui.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkgkeep.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yknscjkn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2htvlkgeh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxjzlq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcxbzoy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcplujvn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2crtspyoy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgqlxty.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnjgaqn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdopczi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfvrdbo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsiirjy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlpnxkj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgzveql.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoaolyk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaonkci.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nclizgpy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwowboit.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvaikno.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqatjse.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhtlorr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pbijywmh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ridtrwtn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2riqfrbny.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbtflsq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqktits.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iafelsmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2urwhmeuv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qruegona.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2golnbdho.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lhblajpt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwkvyor.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bybtdmkt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgiucwn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsaerll.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2onudmubg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpcrsfe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmbdthr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxhlkzt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odwqdnpp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqgldgm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubozcawb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfoxqpg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axncspki.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcurkuf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrjhrol.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpcgilg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgdjstc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qinkjoie.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhwxccu.html


<!-- 参考信息 -->