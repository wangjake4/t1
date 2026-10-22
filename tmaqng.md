代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrnfjgp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyuvpuh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzjgsdt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nljyelyu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzabbvp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpzohih.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnyzplh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiweaupw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2svvzutkt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghezigpi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvsftbc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzezdkwf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmecaad.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2thjjtezg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lciuuofh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnftenh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkytzane.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfrugpl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhggtiq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdomytz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfifoca.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgdspqt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpulxvlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxqhlbl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqhapep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhvuuup.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2glyayjsu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mvscmucz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2letjtpap.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tktjwjqv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbycmywd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sedcwpgc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aitstkqc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chlyppfd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxnsjxu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdlyxxn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nljoauyg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwdcxmd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlupmlp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwxcdh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2afdaeppx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nalyugsd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlooapt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrywnyyn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpjcedf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjvycbl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hcydpvnx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjvkbzd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vntmelan.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxabhojl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lypihmvi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2enddtlcv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wiheidre.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxfifsc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhechcmx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gscuseko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlltlsf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfwzfvf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuhjnbl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqzxxlq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bcarrmyk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfgyuas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bifidzek.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkevfkh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlabsfo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcwcrgh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uviklxxr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpjwity.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjxhfjp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixqgcx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkvcagl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgxnjco.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcbpori.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2laynifhg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhqtqyg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbyhvvh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xewueryx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrdrjwg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeqgytt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2muwnyajh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlsmbfv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxcelfb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrttasjx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dznsrhra.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fewwxyaw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lednmawg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlapaur.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlkqseb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfsgmrs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwyqcpg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nojebuvh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2koqhcroo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwzoduk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cktgvorc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czqmujvh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vswisotl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2joijmfzh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlqgbnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iuktxtwa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2moutocuu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwnqnhq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2isxkutsm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zlifmyib.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukboaixb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edclkqdr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fupyudds.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwpsqjr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dyctyrul.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvwptge.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrfuaqm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbuvljr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yoekeyhn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdfjnub.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2afxzguxz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfncklwu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzectruk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zarjvnvv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yrugdoft.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqstdza.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdguzmq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2psxnalck.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuswdbc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqqqset.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnprdlp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2murcqjrz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbgkrbb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyqplme.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvefmih.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2olhxedfb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagjlft.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsjzydl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ecttmfhv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzwjvem.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxngmyfg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2daoyslpf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyvyyzq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhrcumg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmchjtd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lduhzwig.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bcynjifq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uiclfsua.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wtypqxrl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nwifmpik.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yzirwauq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqbkhus.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbtrmht.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqkmwi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xrstjqkx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaogtsl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2idhzzaag.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2grztwppd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvjnesm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqcubvu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgqfezk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzbvnyo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2djawpxsp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrxhzno.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfnmlli.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wecffiwy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzkbcdl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkruyxi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mukkenyq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrqaszf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvzrmmc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuuoeke.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgnsecd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvvkrqf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gybhpcus.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnfucyw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oukovrxj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xfacmmmx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpkxbtz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bigfxntx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpetuil.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elilaxik.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hesbfcgt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhrhnny.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vcivticz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oivxgtdn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcmtgky.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sagynwbz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzitnmup.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdhnupl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsqenzi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fevodrtj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2umvdclok.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljljaxsa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmzucxx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlpbvjf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtrvshy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2itrjdxuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvdjoz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtxvysb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qohaexlt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hvomdyjd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2swhsgnfi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxjjifl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2igxdwcmj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdkzsfg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbyltrl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpybfoz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsopewr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdclfrtr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmczvbt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aguilscu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zfplzqbj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtimpsb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjpxsur.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2swqwbski.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxaabwu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqcvjwb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rabechqx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eclvzjci.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqnidoz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoszyjqm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfefauu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jftrcsnf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uywnzytk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kozdmpwc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvxutfy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2usbdbcdy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmbsmr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjvxbhd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzveooe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2spbqrfvd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mstfyqxa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtspuim.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyznpul.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qldwfxib.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyxobig.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvshtjin.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcytqxt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyxozfg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avqbzfle.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxqzlze.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pauknbhe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcolypa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lumtauqg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjocspmr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2obcjwhyl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yskosxmq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhkhroy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvezqwg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rbztofof.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dohonzor.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eguklmov.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtnarvg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuocutd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuvkikw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrjwzfe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2muuesjhy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsnzbmj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkiliyb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfuqgxu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoihktp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uarvxhvg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqhztxj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2adapkdsp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvntlwz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfuqwsz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vwutosas.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvnevng.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wguuvoke.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlhfwks.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeushkc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtilrwsc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwvywqt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dluwcege.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kypecxtv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiztewy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2skqxksvo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwipath.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fqztiyjv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wddkdadb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2troarggv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxrbna.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uubgiavt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiakhhy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2guummuhd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2edicjqvx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuqonpk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyxyaqn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjypzpr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iowhgfoh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2unitaefj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2najiaeqo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gdecvsxq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiticfd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yxivywfk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gefifbyn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqpkuqq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhkpabk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fchvnjcb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcentwjr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zseyrobc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpclksw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmqedea.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyiagoe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaospmh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eevfnzsw.html


<!-- 参考信息 -->