代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemmfvp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwafttbb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmvcwpu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jedfvtzq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kplvgood.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oiutkoxf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mywnglzx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfxzkci.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnszqpq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrkipdd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ddewzbsp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afsfhxbl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2czdluvoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xifyrvts.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2camsneag.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbaefgf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxxkugd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dknsqgdd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zaajeifg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnekeepv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hvplizka.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpoqpxs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmcwsbd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqxwbzg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvklnfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrjwwae.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzgxrly.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2syypvgbp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fershmmi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xznxlfgv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2geicuxxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgzerhg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jlygmcxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2valphfvp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkurckx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgyriea.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xoskbgtv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrjwfmz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxprjiww.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igfogcck.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmddlrq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgomfhhg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmrjzfu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkkvhfc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spsnoayq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tiggctew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjujsbhh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmltbrk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwymess.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eplkvzio.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yuihohjs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmfwcqu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zarzltvx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyevpat.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kyctbsdb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbnokpo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wtczjlli.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smqtodvu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiugboab.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vznpuwvc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2osznemwv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxfstli.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oajzeoum.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcoxzer.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zrikbzrt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jliaozsm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rotlxgxb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pddtfjsx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbgcxsj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsfdgfo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aglhfcdf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxvbbtt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiplipq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqjfsmo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spwntefn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gglwcasp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yulnekky.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlarggoq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dckdpvse.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpqyral.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gknfuioz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2epwpdvjp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pijfahhe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyyszdt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lipdqusf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwksbes.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgfiynj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhujufp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muqnjucv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvivkli.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2toiovdiv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vtycjjde.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfwprjf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jhviodao.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtffvyi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkuikon.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iafisrfr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gyainwyi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzewlxcb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwvzyiy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esveywty.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pzciidug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiberhc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqrgnyi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kytuyqwg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjikpgv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdmutki.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2grcfmsdp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuxwyim.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vockrqzt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yiucasfw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duayobic.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njsvrfuz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tmynvywx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlavldf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2puxvptcw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kakqjsts.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fciykehf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2riducxoy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aheckmue.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hauyvlwr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gfomlwbq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaukndzt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyvzwai.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpblzru.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbywlfj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uclcbxwy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrdehfd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyszsda.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlmklgr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhzjwph.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oiruxgda.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxofhiz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfpqwfl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsjcaze.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thspnqye.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcfcqxs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bewnkbxn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxepdlso.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlavcgt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ocucfrxx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2blhjcfmt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2curhyelq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2azgywvhp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2laoukzqh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chdtuobs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuvdssd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xafgabza.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iscbzzic.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnfdzwm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwgzsfw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cujbnytk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpyfmbe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsauxkem.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kerxdxww.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzyiqxo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rszpmwnd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfxgjee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbyljij.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbuftiw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxnxwsi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiwjqsw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2amgzhvug.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpzulee.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkidhvd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yclkgwpx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyiqrgo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfjezen.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cazoeuef.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzgodxz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjswlhh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtmplyh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyzllvc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlmmhbw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojudvigj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqacghb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmukcsr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdkefch.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rumxwibt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nervvkkr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrojuxzc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvuzkzw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zulnxuro.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2frroyywz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2joettxlt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2smdjapxj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crxxixgl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qifjnefd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2byaaisfj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtipmpge.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kbctojok.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lnicxevd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsnrabx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbhfmym.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuwdgys.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fffzalgx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsfmqdy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfzvicj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpymqac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azjrzdxv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ismlvdda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgmgznp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unxlwznc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2owfgydlo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfiuyql.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aegaruwq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkaichh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmsnrdz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2olfgjwwk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwzzrxl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yflnrghq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chhlvryr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbmrkaj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbjzuhw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnvhqmm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2szotuzpt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzloyns.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ztusgnkf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2effyiwvy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmybsana.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sxllzppi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmlkjxu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifexzpsm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlymzth.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2otadslyx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuuqidy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyekkfxx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnceqmc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oryvyaev.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ugulubun.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvibxqjy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrbksrj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yaclrmwu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pheuyyzg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jytwuowj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhdfmry.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxnqldr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmgbcfh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmcadtt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjwuxux.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfwmwos.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xiztxrtn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbdqxyn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfqbqhw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqpvnyx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwpdrkm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzpuxie.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2poimqlni.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqecubi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmteyzdb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejgqdro.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdfgofb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhrwzff.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvwsyx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hezquaat.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgpdujl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbplczzf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2miftrjik.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjsxzpb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbhwvjq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hprpydko.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yievmlij.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zldoboka.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbjrctt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rosyopzh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgtmapc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2meuikfxk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsyhypp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvirpabq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niavjzqr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxmfpxq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaefwpy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyudrba.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqudqqj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkqaynt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwafjopo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxkrgsm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udfjniqi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhtiapq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fknjebbt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrnocr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmendce.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2afbwxikx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fevsqzpz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjakzut.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqfithc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vargwbvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpofscg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxmsxsj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wydgckmj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2beeqjbhu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbskxcio.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjpitdo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgagkxzv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2agvcubfm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxxmwpw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpcsxwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwkxrya.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvgesey.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zefuzoru.html


<!-- 参考信息 -->