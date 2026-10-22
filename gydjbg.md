代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbssighf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uroftmew.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnltchm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cecjfhzx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdespgi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2icqctuaj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gfakukcf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbxqfrx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zaumuidd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2drzniyex.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvscznt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkccfzd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpepbos.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofplofoa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avekjrme.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eixyegbh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znyphddx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pikycrqx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbzlxix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2foffinfm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpeimug.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edssxkoj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qeawuypx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhjsxut.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xryhvxel.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwszozp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdtbprb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxpfjlf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwrwnoi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2numqdvus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifrnqnf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrddeybf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoyisim.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvdkxux.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2epgqnpgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uojdzmwg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkifgsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nexyzhcj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxkeztr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnhwwep.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iawfkwve.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnasmfi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnztqdpa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tapxalow.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wbadbpxh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtydudv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygstqzmv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pblfmbxv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnogpfz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaydzgl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgckszog.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxfdkow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsgsnlg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxrgvqh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxpgekb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvnkipo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gaolgcic.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2unzyuptp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcokxos.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgilhxl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxnskfj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbgndnb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtglvvk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vacobjhk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpjsmlq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuumcjzi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gertvotg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wlenprtw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlentaf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2svzctger.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwbjrwj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfelrrho.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgetewsf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhztkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ennwhbxo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cderbstn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cecpwtel.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2awocofea.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzeowjo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2weyptyxi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zamkagoe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkseavmd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mttmkpwo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mytlklvp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfhqfpm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sogqkqqt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxukfsbp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rauwmseh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcyvxnf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sprqdycb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhpxuzl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ndslcbdf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxafwhbx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snhtafyx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2abbpqxdx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2owkrqvec.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gquukhup.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2koqcdghj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2podihyrr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwmxudd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evwrptbr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ngadvnfh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdshglek.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btwmgsnz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iublrnwn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tmszdrrs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeegfzg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2attwewoy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fsahpili.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttwvvn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2anzirecr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwgktfn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lshierjb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjptghp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gtktxntc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfhjkxe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2primkhys.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnarura.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hmppppkn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhhjlvb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfyobtt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuezdns.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mzflacej.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrvzbzg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjcvfrr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lrszsusa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pegglgze.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2capkkhyo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pduudien.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyghocy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpipfxx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyecvxy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qmorlyss.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wlghgjfv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsokgln.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjferdbp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2geioyzcc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsxdstj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azuoifed.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pofuysxd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yhooocfd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbsrcql.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuprmcf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2okbxtjbx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqzdsuf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qohfnvgd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzoqvoe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2opvgvhqi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhklrzq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxocdzu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oshwufpn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdfqzsh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrfunsm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eovcobqz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoolhmd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzsmwdp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2adxwxmcl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2conhqely.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2otnvkpsr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvmukze.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2exkaawnh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxdwcby.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoafusf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfcxzsq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjlwpiq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzvtaku.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2icnbxwfk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sehzqnzj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tblujzut.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhikqjsu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhujbraq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnsjfli.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iyksdtaw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmekzxy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnymbcb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmdcxaz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwhsfgp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqlxyim.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvhgxhv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlgbzac.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlyzbrc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrhssnd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfvoqls.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkvizfp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbidnmz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bccdbhxv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnqowjr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmubrtt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjqavcd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvtonjs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcxbssp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nozvfywl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwanxqjc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmjgaud.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vooasovw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcunwhv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeelomi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeqsqsg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tooovfau.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpgmnwe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2audabczb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2errhppas.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2joqritsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdficewz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yvacxjxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoujoagd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwiwfvl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2keawezzn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzcsfhi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2roouxdzu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eepgmfdk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2clgsjgow.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspitiu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2avzhxgap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2synacxkp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuyysgo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjczftsk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqiviiz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2akmywbop.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lfygjtgq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikakfwux.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wevieqna.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjakuoe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbavdtl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lfddiseq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zndvbfeo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2paorqlan.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgodruh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsusfweh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwsxrwk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfsmrdo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khspkpfp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrewfdok.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnmbyls.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeghwadi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmxosyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrctxnzm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vffjgukk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pgijyppt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qyibkbwx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnnylvp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tujxkcew.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qajavvbg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjthomhw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjwoflf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwtsmbq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoklqzq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oaddpnqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2enxrmirz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xynxhsjp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjvbphm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qtimyitq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuhbjfa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2stgrdnch.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjhofpd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vohzryuf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2smbmdhbn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2waypfckn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbmeiib.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jlunnxpe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcyifiu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbhwqtl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygkgpop.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efslrhvg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtihtva.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmaiinh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzlbrzr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpxfsal.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2glspmygx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdceurc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvevuyc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luguvscu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wtajhdwb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvouvcs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jecauxlk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nphrlgnv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cvklsvwp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzidtznk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsnysxg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywawatz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiirafe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdnzfgd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfbajdy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2toexymky.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtdpvrz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpajqs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuskmea.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mindfqts.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2goctbnci.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiqmvjb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xnthteep.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eevqofux.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbexbsc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uggakgry.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohteswwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjssmau.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfafdo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qizprbiz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwdizrq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdswmsyf.html


<!-- 参考信息 -->