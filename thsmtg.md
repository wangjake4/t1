代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdkznha.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asisnfrx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuyacub.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlagepn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atlktalo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csuvxdgy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iryhlcfx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfjgmqa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2goqhheku.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slgqtqtn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tufulfit.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xztyglbx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zigjwvcp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wucmwkyp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjgfjng.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwdycax.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ituzrzhc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxmoei.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvmcgfg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqdkvju.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2favqqfbw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrocwdk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwgnzfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbagtmh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2maneyvxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhouvydq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfytxiu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2clfqnmad.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2icqilosm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ncakolpn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qidytlhd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2numhjigj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrejczm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2anhwlpsn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iclzgzzr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyflihl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhfdgc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bssuprko.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmhzdsj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrieawu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxgthlw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2udfxnepg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxkqabv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqmrbij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqdvada.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qaejzorm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wumkgdme.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrevclv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ngducmoo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jesruusb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2luoioaej.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2trjomogk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsixihf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzgmbrd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uiysmkcw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2flbvkdab.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2goyzjcdg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyyfumf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pliikjjy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjbshtr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eojwnomd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwkbktw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zffbwsmc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yauikqdf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kabfriky.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuecoex.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puguqnvi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yofohkzh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojavgjpr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrhyyhb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cafeshdi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sccywxxq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lubevajk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzglhha.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyczfjd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kurmexcb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhfpmsl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yslboync.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unimdtjf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2euxmvmzd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnqpfkq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jutvvuzw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2djbiwhvo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjapakj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxbpthe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2homkbtea.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2syqvqdyr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlxegwr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anaksqqt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbloxki.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgkhvnr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqrwzog.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwedohh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvaoeu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envhrxxi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqococr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvscumy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqzqjvr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vldxgmqd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqesacz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2czsxhfkm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2risrbjce.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsdobdq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2solzlhlp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbrgjaj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hgywcyea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eennrzni.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mswwvquj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkztxmh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgaeibi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2smisyuox.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcfpxuw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gicgvrfk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zueymbsj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmxmvig.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrkpyte.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hqykzunv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hefzrlum.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkzqyjw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2roqdilhc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ayctalam.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2outzppcj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vxspplht.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jihqkhhx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emjeqhuf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzbqquo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2deiujxgk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqxeptn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqltbhs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvkcwol.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrhrwjm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wehdcwma.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2guxbvvgf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcfikml.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njddibsk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlydpub.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmlsefd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqivtjs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ithgbprq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zaarztpe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2coinkdiw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zegjmvjm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrercqr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmrkgfx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcdoioo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obnpmyzl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfbksav.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2brdelslh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlnumyv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlazkzv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyqfsuy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqzwepv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxrceeq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcicwyv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwpwkop.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aoysvsan.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2drverxhb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwaxljw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xotdazhu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrpvxli.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2plkuykmq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzqfxkh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jruytlmu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcshvws.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hyphxvxq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2swlftkrw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kstqzijy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzaikpn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bayearvu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxkaghl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaujnmj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkaznh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzdueao.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cvavuobt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdwoyat.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2focbwlnf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bxckiiwp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cipdpkir.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkzmaht.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcdooda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfqctju.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvldlfe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoctcbt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzcmmjk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjtargd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sokbitvh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btwqcdpw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgcoswa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lksfakyl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ublloctq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhaedze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emlluxnn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ahglqbpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnvliuq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgzhhia.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iigwldeo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwjcwnt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnwutnm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfujlfa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuminag.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2owqditql.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmoedcd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrznvyu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwnbhub.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mylvkqdy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2velhrrpc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gahjksck.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2awmxfvjo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2syeyuglw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvshncr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yggygecv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2whrtzbfq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iesbevge.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2huhjsnml.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhatuihn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekngvxlt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tssnpezg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnewfas.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kamvybrb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrpgvko.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmwppii.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgkifcy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmheps.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdvpkni.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrgrkmz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2whihlrfb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxbdgut.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cdolcfcl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrawtre.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cccuqsps.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnylsav.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdinnwtc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhvpjxz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2majzgyei.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlakpeo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbizmkr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmhkcql.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lwacesca.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2smrvhmte.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdgxmzb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwkiqsi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpmqrzp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwnoqzh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnzhcrz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lleboqdf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jlucawnx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2isbnapoz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzjiuhi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2azwxhrjp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dirllook.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2etzplobl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlmzulr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nulvkcri.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pugcllpr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2etbqchwn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2thqxhbyr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhsukum.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyqhprp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2udcowszp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omuwvcpv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2efudwwmx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rloabpxt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mopqvmsf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2heygsrft.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbqdota.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhkqpfy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cusostot.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rguhtjow.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2anrvajjd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrtpirw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzqhcpp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drgrbpuj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkyfukz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2szpljrwy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaptqun.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpblfvjx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhkxndh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nufgdijk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfcxilq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwwlixp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyvzehl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpmylkl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjafrr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2igvbqhwl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kuypkuop.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjvjajq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdrqpld.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhokjyq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2siuowgtq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuxacgx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uawgrckg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzpgzst.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qicjfvpg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2expnkwcj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avvmdzqc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ariyxgvr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccixbwrs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyomnejz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxvwtxf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pyddrhmj.html


<!-- 参考信息 -->