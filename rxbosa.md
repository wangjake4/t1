代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdpkepc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoqflcm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nufeuhsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrelzjx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zkufnidh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgylwmz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptczqhfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kujnbkzf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjoynx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlpbalw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwnimpf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tertliei.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yrveufvy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jabyyevv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdimtzs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuesuka.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpczvjej.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdihbtux.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtpogfw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hezsyujt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2atbtbgdj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2solktnzr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmpeewp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pokytnvu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qofhuwfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vujaaump.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuglqie.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzibuvq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuurfmm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkbcbmk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wanqieml.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skpsabkb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xomcslnm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bggbgzfk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkymeid.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2agiveryh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeupgod.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiffaek.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwztfwih.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dheqctfy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dakidmal.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slxauefm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsdugjx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2davftxsb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmabwwb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsurtsh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnjpjsm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uerltbgi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iccgxvkh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiunosa.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2exkvpeht.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwllnzga.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldxuwd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyskmkn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trwxlufd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2taehzvhy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aeufbmxw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qfezrjxj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mowziqhv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkctkyfy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lfruflhq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsgycry.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odrdsbsr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmfujsq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jljeehin.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmbourg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsktqok.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuuftoo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpykhhce.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhfxpbn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtizwhg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxywukh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eguuwvfb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjownlb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzapygyf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsrthwx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xiceifna.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipprekyu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apyqbnkd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpxiuko.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phfzktaz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thpsnrro.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdtqev.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxkpeia.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnponjg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2luyrnggd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vffocjyl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pibdhbzv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcugpoc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2twfjheew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkpuafk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjzbko.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoawmix.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqwjowj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcojsdx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbwcjgh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2idltwtmg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vpunxmfq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyhrxuw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgwrtgs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiglffv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hifjiytj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpjxsxm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmptbqw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xorsthyo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jbghtxlu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmthugu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ywblgyot.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtpxzwq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2owbbljap.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeyvuwq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2anhijnsa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcwqvks.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2slodzpxv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzutpht.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjftslo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2smmpcnpl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrojigv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jhymmhhu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjiqahs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dgblvzpr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbxzvnb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbdovzp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iunpzars.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sglvianz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmzrity.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuethpq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfawfuwp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2degtrhhp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqhuyg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttafzoqc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2geadqhbw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2chkwgbbm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mefydyrs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzmfdon.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnddtea.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqacdbx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbjnqxe.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2clnrurwo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fygxqnkd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dtndlkmf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaymbkg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rockeppx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tsauhllm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lcicrrcy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jscwqsgf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbvbhsw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrejhjb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zwucquph.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbxovdv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2joykdknb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrhlzxl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdolcwx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byfbvuqa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqxxjcm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2czspltmt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzvzuao.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2htpgggxl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmyhnoc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkoxyvw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2knjwifma.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrgwjhq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mbddagcj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnetnqv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pjajtthc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2prjjjmeg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcceaqwc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvevnxia.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eoexshlt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxjzlzx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkkbolj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nflwypen.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pehbcxun.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qtstslmv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mssnovcf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nrloprau.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nceeswez.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnxstne.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfyofmp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpajujo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rehhvksl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbyxarv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kttvscko.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpqgvir.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbzgohi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2geqdjsmb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjetosz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kudneoaw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egjmanfu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2npivgyyj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hhklnttx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvnngqn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2roseabov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cydclyfs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2udxrapgq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2konpfpmw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laflhmxq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwskbrps.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yklttzhq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjgjuhl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oakiqtbu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fqanmzyy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2duqdoovg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ppexhlsx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqvqwua.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbosdnjm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2miyudnzs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzwavlo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmunqkca.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxnyjiu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbrqtig.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbecoqq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpmtrqr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdiefxq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhnrejy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqocljva.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2egizxugw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhcmpep.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bicugelj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kodaqyps.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzebmnhx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxhzmhz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyjcvfe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szqlodkd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoivdci.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jexnnqtb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaypxej.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ifszpoie.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzfeodm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdgjwez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchjfwis.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kihykosj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kenmmwgl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dougtxhr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyclbnox.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfybsoe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqmtyuw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgmlzue.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yupvblli.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2owbyppou.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzgebxp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jryjbhyc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnealtb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gycgolfx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmhyopy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzgifyv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawzftrr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcaenec.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaelwut.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxewjil.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbybamto.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2saupsejb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrqxapv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmvdxgq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgaqylg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jneqvuzf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkhallh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpyhrgn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdanadh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsnqlsx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2urxdeadi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egdlnddt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifizhyja.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mglyoikr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxwithi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yexzapqt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2realslqo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juvsogdq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pzybmwcp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sboporbn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqtigwp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmdrsxq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jrndgqse.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcjihoh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgrkyqc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zeirvwtg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzxhodm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoyssgz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tzczolue.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaexphf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxqmkuy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpdoewc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmgetuz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwblzacc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2egyimdan.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnjwjhx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhhabvy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbbbvnr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsomxxh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkacktr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vyisxskq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgexpqtl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ellrdkgf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsysjgl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcgvlyw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdadtgqj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcalotgd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfuahwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozofipjp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaygwao.html


<!-- 参考信息 -->