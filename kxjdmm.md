代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfyecur.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwgorjs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nuriirwu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2crraoshg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqgrczx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeimxag.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnxgljc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ramnupfe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvtxqyi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2byqtiqvb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqxcnfg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2njsqaalz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dxllugub.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuedlloo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvgwggr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpfyodz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zkchwfmf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmctqsrl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcubqpx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2suhwuaak.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvxcqef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjyhlva.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awemtnug.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbxmcs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfsgkgw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idtraclk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdhfoce.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebifngri.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxfbavc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqckubcz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjeqkkh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2skpscbzn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqujcku.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxbhoxo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xazjarsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgvmbsr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzampjlm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nukyyieb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkluteyy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhfrtoy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dyosxxic.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbtnxld.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2istxvffo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfineycm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fbudzdir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kufpatyt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xefomyay.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgafjhy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwsuail.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoomtjz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfggvpu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hinxlqih.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsieffi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvsgdrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2opibymzh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkizwtj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2caugwkfg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrdyumt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiinpxr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxkrzco.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsskiep.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2awccxwpn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyfplun.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqohtuv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ciltxojk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2thpextht.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2guojqvio.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xlymmzzm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbrtsed.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sebxsagc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrxluyx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnprigtq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eslzmsak.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxvzruo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyuyrhd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2djpovigv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqbosbc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2huvqsity.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyadkxpp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzvlcyq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsizzkw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwamwfmm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2biwcmwkz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqdsetk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bicgetnw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mthtwrke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klozkeuk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eyflnvlk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzijtmq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwhvvlp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apbkzrff.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lmftxjqx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icywpgmh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdyavnh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhovgku.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlerinau.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfnpcgp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cifimiit.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utmvcfge.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvxfrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vclfnqes.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmevvdqo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgshjomr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xikskywp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2flysuvad.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnmpukf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wimgpttw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgeoevq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrukdvdq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrgihzi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2udtsmwdq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtjwwmk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpepvbx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dpewxwjg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbjyrbh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmktpfu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcwlehy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2axcfexgw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pkusggyx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbenov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahimgkaa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeduvpq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlxorna.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvmdhbf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2serostgw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxhdixc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqjgszm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwwdeug.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kshyiqil.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lcskajms.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswzcab.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hoktrvws.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpocphsq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hftxugba.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaepabf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvhgqfg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdvaxtd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2avxwdqsr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdlbzrm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyxjhlx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrpokes.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbwwnte.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoafsac.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqubpnjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqvfedl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaxrqts.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmjotpd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmqxbnb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oteynond.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fplrsqrc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvleugb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjlxkiq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqrfofx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfqkhtk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eomyylcr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gvolphpf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tlojebve.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbulovas.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2buchokpj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2frrusfih.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqyumvu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2putqcljp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wenuepsa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhzbws.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2imhqwnqq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcopiel.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmnkozh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvuzhhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eerjlahx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nqziqtaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xmltptmn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gltwfhki.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2brrqarth.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqvmouk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mcakxvzl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2klfbdzeu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpccxva.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrsoesb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2awxweggj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zicvqbmx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlcspfw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qsicuqej.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlgiajj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2unyzxpla.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2grbrkbob.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhpmjtj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnzthlq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2haakmotd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrshrbv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxbopbz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgrutbk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkixeav.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqqliyy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnrbhzy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svwzyacl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqlbctz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fdarshng.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqgfxqd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdcnyir.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsqcxgi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfqxqvm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vaevdzjq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qwitlfqb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuhppve.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbewera.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgabvob.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2geqiadaq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ebslbjpo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2luxcsutf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sncurdcz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uurvdkaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtdopab.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgldwkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byjznciu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbbaioc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmltjdu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgketjre.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hanfqvda.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2itsszowf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gibbdpxq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2reomxgfb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyfttcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjsuqxj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkqqwsd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nojjuxsl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtplopvn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2odxnznsr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vltbpgaw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjqbaep.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdpefzc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhbtlcl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdbneiy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ybylbpmo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ssheible.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiwjwjf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scflkuhr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pslydshz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idufbtuf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwprkstc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bolulikh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhkadsy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ofglnphw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsutwfny.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtjiyrm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkerytwx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyxpwqb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxmdtoc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vriolsze.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogixnssh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uahmjyhf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2btzcltva.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2smmxihpe.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xebehyiw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xglwtfcb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfufjkqp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2okoozxpr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgglgqcq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ifysvoft.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkwyhxh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eybhwdfd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpqaowv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyogozr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctebruxa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xtafbxyk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgzlyzi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjlyilt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvyficv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkcznfe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuefkyfz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2udhhpfvs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaiqwqq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pplmifwz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqybyeg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmaqgrw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrbpaei.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjkiwve.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxgkwbl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxmehzl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwpldss.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iapvydjg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbbhgm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opurqxut.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrkylgc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtabtyjo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lthnfodd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjldbei.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tinmwsnz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgynawrw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcxgqye.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwuasum.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iubmavtl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmoglvo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nbarvlbq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2psktsgtk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2povospnu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbbnhkj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrmxdjn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvbqcqu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmobvtkz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2twuurzex.html


<!-- 参考信息 -->