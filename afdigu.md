代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2orbliedo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exjdgbkt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oymeecpd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfftrcqu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fycxaoto.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ijirbhsx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxookhdk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfwlol.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfvzhgr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcggfwt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqrmtxu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dfruvcqd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcypgfx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyoayry.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihertvot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcriyav.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gikjxoqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcdwjtd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2grxisbph.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaxunrk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhackok.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtigwdnu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxhlrpc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmjrmgo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vcysetfz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiikgsu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvwhszu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2odiywzqm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrlzgwi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gntmeext.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmatvjt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgexvii.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjokrdx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlbyqni.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoaypgi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2skvnuprt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2txpyrfsw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2igiukjbb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ljggshov.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrffkxq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzcjdfz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aihkmqzz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rezgkqpj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibfsypv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxjbtde.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hduuleuw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtjtixj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvztczl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bggujdcv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2shauuefm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkwmyzq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaidcmz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqojebs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwpkdyg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhxnfc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2anlviysx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpdruy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2orsdewvn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2razoptbf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smdrawdr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkswkoj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iplbkhxk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2neqgjkok.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxlxhev.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjdnsb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjrjaxo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkxyztq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbfzgbj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfooxwn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yecukguf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guewdgey.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2whkpgccz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmxptvm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enmafkyj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rruvriqf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kouzyzzd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gogmwstj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfloebv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hiejpslo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khsvmphp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjedejfj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iegkpynf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2icefkfzx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htsmfnpw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfvmxup.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2njbilnmq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoaaaec.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kvymmhcm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tyginloa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lutzxlcz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmvaaru.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjyonie.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlaqite.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lflylbys.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkiwdsk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqnymwb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvwtodf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2igcdwjos.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slydnejh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqmley.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwzjcrx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gusjhdbb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxisddg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyuddmb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhgeken.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhhmits.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtozersm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcdvmsq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2abqkdxyy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2epgmbsqa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gibhsijb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kssjchiq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrqtfep.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhkaytp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bwalzqcc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hokcjgea.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeydcfk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuaqjox.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmatyrhx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjelewab.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uucrspqf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iqndtdbu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uyralqys.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlqqgdg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnahezn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcscinly.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuechpus.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vglitrzy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkbkqzj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxqnhus.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odapfwrn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxegyix.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2agkgdkod.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lakdwebf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhpypja.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qljbmute.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhrhqqu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqldorrv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmxdkce.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lncfplbq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2foibtvjm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ahurgcoe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqtcktt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbvccxz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yrovguoa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgwcaih.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsnooyy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeytayv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrzbubn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgyhdnq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbxrbhs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vckfjflo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2igohooby.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxauwwxj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2otumsibo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2htanmnzx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyumztx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2glrwdsii.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnjwrjs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dejlfxak.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vveyzfyz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2onydutam.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwjhqfm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2evuscgpn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbitidih.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxfjhof.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awkknidc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdwcfau.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmmwqhg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaiwjma.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyqyffd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhpuydu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xotwgcjy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjucmxk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sojbictp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhjidmv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vrypgova.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmxjkkv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrqrqci.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdvkljd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cehnquqb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dytsicoh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdwioxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdofcrj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwgmsup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffuehr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzowgplw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ynulcsxm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlsdnbl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jypazoyr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nytvnykz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2djazajtz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuawuze.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhjdnfl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkycddht.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zubcgwti.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueueafkh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyqhpgb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdntecb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cariruga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2huqhrrov.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2utbonkdy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyypnxfu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddewrdrk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpjygsk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2orftqepz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjvdhpe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcamquv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2agtxiiou.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibupnois.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcscmwvk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwcpnpa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcozgrn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kgobtoar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ziszzrvn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcdiind.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkpnjgt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvehdmn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtihvjs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2akgnvraj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2edacrzrr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2musgvjml.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2erqdartc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alebhuts.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvewkea.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yczxdmyi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaxguzl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2taotphdk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kupchjjb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wwchqkgr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wstvqalp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmkftej.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyeueiw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkgdgfm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjzxndn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvxiqeh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2syyylnkq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qlokgobk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmckosx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwbbjub.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywanglra.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwbjcbh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iblwgbln.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbptpfmb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyghjrx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uubdabnr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwgvtjy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrmwwgh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvqnxvd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxbyfed.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgdzqsf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jogvxcww.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzvhmwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrtisai.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srpcysei.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwalytdt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcjuype.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjnnism.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuemgmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyknjsud.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dvshqrxr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2niuwfydi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wasfzoby.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixhpynx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bklfuowz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emgnxjdg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzvjzkn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvubmhk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2riygosve.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbqzvgz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2reozkhlh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjtcuyt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzopjbna.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwkgdxy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfogzdi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvybyter.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uxelpoao.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqybqqt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sgypzloe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcsilbw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnquztd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgplcnvl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvndnlc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owrgqvjd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsdjbsh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrrugds.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hujzvnpz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xunltvgt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfmxalf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2auomwdgx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxffwjk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2stiiyuhj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uotcmohq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aysslxnc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rthvejhk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rulmihtz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syouulrn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2izlkjpxw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2agltnzro.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mydkhipl.html


<!-- 参考信息 -->