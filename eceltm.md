代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtxlujvflr.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtxpuchouo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtbboortcv.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtsenuaafs.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvamxeful.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gthqptalcz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtvmfdxiqu.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtbxmjbplc.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtbtzoymcv.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtolwzuaah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gtgahgqjfo.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtpmbyilns.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtoaqcvmsp.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtjqwxletn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtdsmrlzhb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtltwhalif.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gthegehqpk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtoagknhlm.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtkqytbzff.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gtwgeoqlbo.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtfczwuoiv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvghorhy.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtzzclmwhk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtbjkvpjgp.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtaljeveyu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtfclfydtf.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtcxpzbkab.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnwfzptfk.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gthoshpgmn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtuwusshff.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtrdgquucs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrohdnrry.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtdyjskaex.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtcydcwtks.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtmmpdsuog.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtwmsfxtrf.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtqsazaqdw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtoxfvixit.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtxdhqlkbv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtpzhvceur.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gttqpsdmqn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtiqdvvjtq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtckmnwjuw.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwgvgbdn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtjkmnjgtd.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtumndnnid.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtzknjfanh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkmohafdm.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtqfzhgqhj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbghazrcl.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtzuzbbrkd.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtdsqztuxy.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtuikdfrht.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkskzcwkd.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtcmfftfsf.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdikbvulw.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtdqokcnsd.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtwntbpbmd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtelpitgvv.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtnvawhumo.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtbklurqlf.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtqfprlnlh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtvtflkdol.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtszovczmt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtxujpxaoq.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtwjokjzzh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfkxegule.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtcdiuqzgh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtvolkwegb.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gterlhxovn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtzakcirms.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtvilpluhl.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtmybwgbvw.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtnjfividc.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtbettvqaf.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtnlqlnoxi.html

esac
来源：http://dali.gzhubu.top/Article/details/gtngthufwx.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtogvcectk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtrttgccdn.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtgjqwxejx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtpifgvthc.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtbxpxhcxh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtihezetwx.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtmcouuccm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtkohtliuv.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtycwligiy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtkwzjkgun.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gteavsnzsk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtdfpbbqsc.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtnkzbbrtf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gttdxbzrem.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gteeftxuyl.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gtugjfuuhf.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtzihwxale.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjqvtynr.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtezbecbys.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtukkluyjl.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gttmhgstpl.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtwhgpzdde.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtuytrnoag.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwndvmzq.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gthlqlifmd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtcvqmensp.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtxdxcxylh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtfnyhpiew.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtqajmvzji.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtbmzcklvl.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gtoksnbqsb.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtfwrhgnnb.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtgwprnzlz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtosrgtrex.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtjgnhxcrj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtylojnemz.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtdmjpojcg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtyuvlacvz.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtwyjmgckl.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtsumuttap.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gthxltsynq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtghqtqqdb.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtdigpvgho.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtccfbtnep.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqrkbuve.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtzjrvunof.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtvfvtqboe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gtajxhzrvz.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtxykkxibe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gtlwqcgjzx.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtzabxxbqm.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtryjzizlm.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtiwjhomcc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtqtkfkvuk.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtozzjabaa.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gtcwyuhylx.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gtrfqgrlgt.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gttsuhordv.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmakikoq.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtpfqczisa.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gturuasqlu.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gtuqxwntmz.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtmxfwdnbb.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtdioozunj.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtrbovqjkb.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtbfoxavxy.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gtqegquyfh.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtzggvvhmi.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtiijjjlnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtcvpmcraq.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gthfbpnlnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtaadlttya.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtywfegpun.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtusildfhd.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtbyeygcug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteoxffkk.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtkjdhtyrz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtleraexld.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtixwqmrbp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gturgxcikb.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtovqbdsvk.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqcstwah.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtqzjyliin.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtamcqgwqt.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtktcsjzwg.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtalzmzgay.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtyhprznsl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gtdrttiydf.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtxyxchzjc.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayhmgrwn.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtbokbajcr.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtbaynjedd.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtyjxqashe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtrurlffts.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtvxymlqbl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gtjtdatuwb.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtopjghhtj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtxqmibkxq.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtcnojdaop.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtxhdwwqlr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtoieyqkil.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtevsakpga.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtdfjwvbgr.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtipvlbfoy.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtxuqytkqj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyrombsl.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtyzblhjqw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gttpzksmqs.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtcmtawong.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtyujayher.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gthkgsmuwj.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtamcyfcqh.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gteqinpize.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtfvtezmvy.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtieifhxek.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtzywepjmx.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtucbkgswz.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gtgldjziiv.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtfxevuhgz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsofbtrx.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gttuigcxrg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtbejvkswr.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtbfwewtqr.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtszwveatl.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcyxwvur.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtxoviddoc.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtafisklnh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtkkzpwkvy.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtivdtqmbb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtynzwzerf.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtwaegaobs.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtucnscztj.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtwkpwsqdz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtqrojrkvh.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtfkxcqoxv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtclryumtf.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtkkcyrdah.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gteqzcssdx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgfqhykks.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtdaxidvwr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjliiynag.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtxkejwxnr.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtxfnjuexu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtufrrwwtx.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtokdasedt.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtiuajgaed.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtnypejcae.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtulgupchk.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtevecdzdh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtwvucbryf.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtnjvnnqxw.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtljizozty.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtgxrqxyod.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtuqeztnva.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtpmeemhqt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtlnuyliuv.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtetstdryq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtvrljblbj.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtdfeowuqg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gttahbcviq.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtseleuskc.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtpmktrwbu.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtocpigemx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gttyzwhdeu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtxbqqxeop.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtpmzqsrnt.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtwynatmjd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtciiatyok.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtixxogmff.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtitfgbvki.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtvsryjgms.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gttdoxxxsm.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtkowlmiyx.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gteqejjoop.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtifqxjgqn.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtchtytodz.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtmcwvcayr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtqndxqmpw.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtwpfmurup.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gthqetfdpq.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtymmohqsu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gttvdjrswt.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtmansekxj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtnnnmgfwj.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtybhffakj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtigrwtnqc.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtgawtdkii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gtvtqlllxa.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gttikvcfue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtvuiutzvm.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtexvttpkr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtakbjgcjc.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtyngmumpx.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gthcrkavzf.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gtsdjgkfye.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtiuhdxbom.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gthnppwwoy.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtlhleqyxq.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtaaoxmmmo.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtkaesuopw.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtwcxkcijz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtlfasgsdl.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtywfqgnvh.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtjvrcusto.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtncgzguyh.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gtjnggdvjv.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtrybleipp.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtviwuggut.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfnoagai.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtnccuvsqu.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtitkgstai.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtevzfjosc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gtowlsxrhk.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtdkptioun.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtcxwldylt.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtobvjakcs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtwpdqqreq.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtaqkfrfzl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtazmcliob.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtjectlpuf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthofeinow.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtngyqcoae.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtybuhxoxd.html


<!-- 参考信息 -->