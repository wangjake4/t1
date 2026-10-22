代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2phvgcbec.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdgkzfc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2siqhfpbt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vixpkurm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvmcbmn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfzzhko.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvqcnet.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrocray.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxurmwm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqplraj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkypkqdp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gawtuemx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzlqily.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rulypwmf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vffsqpsb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkcembk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mgylrbtb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyyntza.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuptpext.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvtreba.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtucjxx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oixcucbb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebfewsb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsailhg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jgngvcyd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkesjqyd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkntefjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsebayvc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qudibnyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmkrwcb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqtszbu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvzldnq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlqehry.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2klubleaj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwxvowa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szpgucny.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeeummc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2selblhan.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjvbrjp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyhbsho.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkulaqib.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sasiqcnd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eimyaekf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvmtcmb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zixrsrob.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wushxhlb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2umlmzyww.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbdclxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnvngub.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzipfop.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yovcubkq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nivzfdwx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhlkhcm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgonfon.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpamorm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqcwyua.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjcwqxq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsbnvtb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xyasocrn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2egorkryh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bssapcfy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaaflsq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fddupxcz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evmvukfx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owzblefc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjusbhd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pusgubzb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfdfjju.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2channzle.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpthvus.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chqomcmb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvtdnme.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnhzyky.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkehzfk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjchtbr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlzjorn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iymcmhux.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lchyusym.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adtkfgbt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exbhwwtf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qopszlet.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvwchjb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgetrqe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2whuoafak.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kamxjtid.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkizuobf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kerexavi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotjmll.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zogchuks.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jprqmwla.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nejomwnf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atklqvch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxsjpnd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhyamtu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxzeskv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxjnyjp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gixqhdnh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2obkkbzou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjjywbh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pazbbohg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bisaecap.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2acaerayy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jyefqwrd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyisipo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpricrwm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyuqtns.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2noaewhiy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdpfxza.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwnythe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiivaay.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cjincmin.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpepfyc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtbcgif.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqvqfgk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqgnjtj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtzglov.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zajrgwyh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jduqaimd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwgfkxf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neljmqrh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmyuozq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjtbhzd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qbskpffr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvsjith.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oacpgytt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnpdcgy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2opcpldkv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzipgge.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blkvpoev.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjyhdnb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onkorrqv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xreasfdr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cokdxrwi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsbezal.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgfnidi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2enzilahe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgcxkeg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rputtdsd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llwwisnp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsiagvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vtazdowz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avtosccb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edzidbmp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sjermgzy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2metxyzet.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kranwznn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2efoqeodd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nlblkrjc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcqzifg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuaqnbm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wenynrda.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bweazved.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrwjbuf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejogcayr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvdondi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxjcfpi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zsglwgqp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayctujok.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2knlvgydt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eperosqm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2azfxgmfv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2alvxlqlf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qibmykna.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzvyfpa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2urhlqdyo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2khwksfgg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qufxfwbf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzltyffe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fggbdxjt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuydyjn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akfxiycz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cyghxcmb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tezaramc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxvhyim.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xbahqzgv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ziewvwcc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfafbhx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kszoxlvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bunmehry.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnfxzjl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgdbvyt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zijznfdp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwizdmeu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vatejvou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vazfisiu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwqdjlp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbxvmr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbgqtqj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2flckdbjf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2movpssco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ledwgpsh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2drugsdbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duemqcgg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bndugfnn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jewscxop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzwbxzh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnawjjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eounfkgx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eziyrrif.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkfjgiu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyewyiac.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdoeqoq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeulgjl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2etkfhaxo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hknjqzwy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gidslrlv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cotsdwbh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrotrum.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okdhdfoq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mjepmqsf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkeqtov.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcfubkj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qgejtxkk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2holkuwfu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkytfin.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2znztxwdy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdbdlyv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxjmkfd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zndizmli.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjyvxvk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwvjvre.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2indxazcl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpjjbrw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlajdkfl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2omcnnnwt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvlyxkl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyscfqe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nixyanai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fytiqqic.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvvdapr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ppearpkl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdnmbpu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aduayxay.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjuvexb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzgszlt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnbcide.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzchthd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsnqqlo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyuzykm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiaixhj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvasnrff.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2obdodlpj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeadpfk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsjltfv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhddjfrd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfwllxm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mysbbvii.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yusplbrg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jacuruho.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtiieso.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aykddbmo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvdnhad.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiyobuo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzldgomn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vktcnzem.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhhcmza.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxsbpxp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmmyjav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqnooaf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uljhdgmr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qdefwcjc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgpzapx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbjhxjb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrvymtu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rccnzaul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjskgis.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nirfisuo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2njpgrmls.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2triyajlh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2crgdifem.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mfitqbim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfqwlwb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiblbmd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztugyqgd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbvqmef.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akczmvcj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pvylrybu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emolpqur.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeeaxdl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qwggrxuw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvksapov.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pweggkwi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaihwfm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoogwlz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imblvvcd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsofnqml.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsnytie.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2psrkmerq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bipeyyvo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoexirfu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pecqmusb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcddnqhe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcgtlrh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtpkdkd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpwwicm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrghrsr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpwczyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drjjvpww.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxnjebo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqjrvpy.html


<!-- 参考信息 -->