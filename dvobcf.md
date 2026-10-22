代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2arfwqtdh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psgwvixb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2venxtgfw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpagxcya.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbfspxn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjtjigs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2obgroqut.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeubjcx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2larisdpz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iatdllay.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2eefqehqp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwdzder.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkaovor.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kquekbys.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2betvwccu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2loxxtxad.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeayyqj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nzghpjui.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wudmqbqm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odndrspi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnaibiv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lttnrxuk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpcvsrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjywpbou.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzbgngc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aogsrqua.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2isirdhck.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ajplaoww.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qllnxwei.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2evlfbszy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvljyom.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfnxaho.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kfocyzxg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yelngvbb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2npeppazy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzofqmqk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsqkjdr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fijecfug.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soyvmppj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwcxgux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpsnrkt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wdveervu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxzmpae.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvfsuzn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvmvcah.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2euipzhbi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cmijymdk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2godpmyhn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dttlapzj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxkwwkf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmksfxm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovteamrk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyqxbxz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lylbjkpn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iaklevlc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oivezscz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjdwyhq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dorokcix.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiofoqi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbhhtfz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhsgpvu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igfagvji.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvdqjnp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcxohry.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzkcfhe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeykrnt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azypfzdl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxlxfrc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enjzrpuc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaszmkh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rreemzms.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2remucrmo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuonhpi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrwvkzd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxawfs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2caghuptq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcightf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjsixwq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgfbsim.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2onnlkrlb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arehisyu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkihtca.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oebwwihs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ujerkrgh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mucjkitb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oczjjaha.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2snxutsbz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efqnilem.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwokaqq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdomseww.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2derlvtsx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akuxwzec.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnkvqlc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qeahotsy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhushmcn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtjgpyi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnwapwc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpspkij.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xchonlqz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jrecbowr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjghsl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cztnfbwv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwihzdm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiqqpur.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvgvwgh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2voqkukeo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpdmfmv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdjsdik.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpegpbpu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zllpbmro.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmjwrj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiqukzd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfrsfsk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkmfamj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lliyebnz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oljvlvcc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2blqfahqk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xjybwzcw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtsmvon.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tktnsqia.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmgryhg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zoabykrn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lstliwnm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tslzfpdo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2biqmnogy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2frnignoq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cprjbqiu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzsgxzc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2trbwgkjh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yomkhsfl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuwfqif.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2efwpokfn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwmrmos.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2akkntjzt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isrjpxhl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuqkrdu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshleol.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsxdxnd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltskjenq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vdndpjkk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nnprvkrd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlqmqqb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cqarzjht.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlwsbmh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vmliwvwm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfrryhz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxyseth.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhhwdqv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iejafape.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2umzaxtpx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpscfov.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kctxagqb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ashdwhge.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcnocav.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2puanevfg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qfglvbrv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoltnvj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2czwaslgk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtaaoxh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnguisad.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzlnerg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxwcbgm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfujqpi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuwydym.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2coyoatdu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lspydfjd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnkkbjl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cierxzso.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpyzjyb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iswxmnfz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dehorutw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sahukqrf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghemqikg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hhznxhbo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnnfmok.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaoxctr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zkabvrib.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xaezgxdz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqherblo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tflpqrhu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlfmhec.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtphmwm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2esmrbaxw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eduhjjxi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgtteq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2idsokzoz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srhnzgdn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2amhukuun.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isefxypg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbbaeff.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwxammb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrsboyd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2reredrla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xanrtseb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhmigyd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmrnpir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hocguxdl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jgftokde.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtdfdn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpofmcq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2boddqzdq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gevkypvn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rygfrvwm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2giuijaah.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjoxmvn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvvauoz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwomtwe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzeqfhx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsocavur.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwiqist.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmswgux.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2saksqyrv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkfkkwm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2owdizfwm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2suromiop.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjjgtdw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxddfjqx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxggwhbn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrqzjil.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrmxbfn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2weudwfkx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbphcho.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzylrgb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcdpwhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hauyoqxw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2khcvuixy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2miijesix.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gagifqrg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlseknht.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhvlmig.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlwhbkk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pstxfuej.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hktildug.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzrvfny.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcftglp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tejfxxbv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cewisqnh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jumzrrjy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkehoxd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2siesvqtz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2shwyffsu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkusyfiz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2htrabmld.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwtouso.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjunwlkj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbqybgg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbzapaq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqhogqs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2exglulze.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqccguqm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtvvbsz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzndhhtv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgargxj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkyqtmi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkajbnxs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ihonhunu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2agtpjxch.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqhztsw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgoeogq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rsddrtrh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfprcbg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkulvyrt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2khrdmxit.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgxgukz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnabfya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnfdew.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxltegm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krhdgvpe.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xswlcikv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frryxbdw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyifvcv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaznmaa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvpufzb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvbeins.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2laegurhq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2drgwnjrx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwyghru.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2snzrtlev.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvdqxdx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vztgdbxs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smobrxpz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbprtuwh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnvmbvp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvrvpmx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqtuoew.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfernno.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjghzha.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqjhxxz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnvnpuj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbctoxrl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzboche.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keriyayc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjlgasc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvoscyu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htnkfktb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjdpmqj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrleulog.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmhmuiq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aihyhejd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sceiwwhi.html


<!-- 参考信息 -->