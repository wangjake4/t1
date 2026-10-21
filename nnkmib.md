代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtjvqydfjx.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrmxmdva.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gttqqzrcqn.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtibboerih.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtubaxquhd.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtzfqutyyd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtdunfjprs.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gteycfxxgw.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkvuvmsas.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtcohhnayw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtfoxsrkul.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtzkpcfoqs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gteidozkpc.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtaypcsytj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtscxbldmy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtyupithwu.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtgvrkartf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtumvllcsj.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gthpckkmhd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtshxorfnk.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtptxnzfyh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtioejjupi.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtppigotni.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gtoprdcxtx.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtylwkzuvf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtfkozbwhj.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtbaweuind.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtjkdtmegt.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtcajgjjcg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtidfhwcgq.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtonviisae.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtslraofxo.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtppxpofur.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtbdimejpw.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtimflctdj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtelqrlxik.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtiezlsgeh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gthgmtrjkz.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylwfkigf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtrykaueep.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtzytbhrav.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtimosanjp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtxlvwyiks.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtyrghfbdj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtivhjuxdt.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gtpjrkozwo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtplhdfnrw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthfmgxnbi.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtivovvejh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxrxbyatz.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtatpyohxz.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupkmlcoo.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtjvyzgoyo.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gtyyxxpjea.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtfujgnmwf.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfhunrfj.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gthfaamley.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gtstmdrxjr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtpjmrabtg.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtpnsnjxih.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtjrjoxnzw.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtdotedjdy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtftwlongi.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaodpvamw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtsgootknh.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtaxicqzvt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtgulptjpd.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtakfnmjce.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtoxnrazvf.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtgxtveaii.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtesymoblw.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtehdtdbrk.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtedlkngme.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gtshfrgwud.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtloitjrjs.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gttrsaolzg.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtjjpvrmij.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtdgeqmaol.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtdqbckmfu.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gteaskkghq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtxxpsqyka.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtqsxmbfvt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtwubstoai.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtqxhuquvo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwrvbwbga.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtcjuvexkq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gthsdrpwln.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtskxpjhtm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtkqznzvfc.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gtbzkxhwhr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtslwzkjpx.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtkkfyhvdx.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtcbbdfaps.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtowpdyfvq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtvwbtqeht.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtfodppkem.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtqipkkwvp.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtuvnypmvv.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtgdctkeiz.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gthgwxutcc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtbqaykprs.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gthdndmplv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtugjlfdiw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtewomttxt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtlktmlylk.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gtqohaxooe.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtjrvdsugg.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtvdrpgluk.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtyheieytu.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtwjjghbad.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtpwvxmuxt.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtlnvawxse.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtwxgfmmuu.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtnipkrnjd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtwikawsye.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtffflqinx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtuojvjqkc.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtqtjiziwj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gthxgpttik.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtzmrkxiez.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gthqpnnpqw.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhrcsqht.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtgwirsvmk.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtodcyuqlc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtdeczrhej.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtskxzuxgi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gthazaxbyd.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtpqhlwwti.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gthwhksdny.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtkfpfprnq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtfkltrryx.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtmmoaqgxx.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtapnjhzjx.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtitpbomrc.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtihvjavdn.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtvsrptpct.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gtjlrtlgam.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gthfpbtyim.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtbuuvcunc.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtvdvjyodk.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiwjusah.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtnhywzqld.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtifuhrxtr.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtdcbleqep.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtbiqfkazm.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtzxuzdcri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gthaiqnxlk.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtjpjcfrfv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtmwfkupkl.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtppewxuyr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtgovjzmnl.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtdhseoixj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtigldohyi.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtgmwvubsr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtoonioedf.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtjxhuohyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtrexygmsi.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtdcuznyln.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtiydaobpy.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtjslsonlp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtlqrqnyrq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gthkktnfhg.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtivmzaaeo.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gtncnsnvst.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtmxzrkolo.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtbymgqrnh.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtogxmdmax.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtnvhxvgrs.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtapjdtodh.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtqavacjrf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtuopfklct.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtibxlbeav.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtjyjrsfpe.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtiaujwzyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtousbtsyr.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtstfrfucx.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtcxqzarcr.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtbfffqlbz.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtjgyolzhf.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gteemsagxa.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtswxwxovr.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gttwnxzmwr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtwknvovbj.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gteodviurc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtnwptivjx.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtmqsjmbqy.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtcoqprcwr.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtcitzzoim.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gttzsgfpub.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtqtobadli.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtqfsfhlav.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gtptzstlwj.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtupoukkcl.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gtzxyhcmqc.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxqektfq.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtsoqnemdu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfzvkozn.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtdissqheo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtnwzelajz.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtuuhwwtex.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtwtclzdvh.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtcucwpizf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtkdlltbfj.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gttqrihcvu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtcvezvkoh.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtnzriqqaj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtkrqiwpop.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtmbxlgwqx.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtxbtcdryv.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtskdgebqq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtprcjhlzi.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtkjfqesww.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gthptndiwp.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtyyixcfqw.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtroqisauq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvmmybneb.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtmjgcggyu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthryahmkd.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtrlwqhhys.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtjrrkzmzq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtfnzignwc.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtuqbnoiyk.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gthbrwdaab.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtjisbaaqv.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtkttxjlcv.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqfhulfs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtvwchajen.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtmdoaurou.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtealxodfj.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtraskwbzx.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtaclfilix.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtpyujnxug.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtmueofoxd.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gtasrvzyak.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtmgigoykc.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtjvxozdyo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtbmwvzchj.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtpxlprhos.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gtnpozzvjg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gttyzoexfw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtybjucgho.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtwmdentha.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtwbcqtbda.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtcmfnjzvg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gteogokkit.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtuveybobp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtwtgqcvzq.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtoxdcdxph.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtwvcnnema.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gttrmztmqa.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtqbplyigz.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtigqzhffi.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtacnpoqgc.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtnxlukvyy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtcbzuwyoc.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtztajhfnw.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtxtcvchna.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtbvliijnq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtvwdwgpgx.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtjpblwukj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtghgartoj.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrbpfiio.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuookxuka.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtjjxvmwkf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtucwcqhth.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtakgbcgpk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtftxlvyfn.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtpiyxozjy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtboldkgql.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtanqvrdya.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtkvjbkmda.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtctyxyiwx.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtkpboeqff.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gthskesrct.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtlswdgnir.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtyoqnicat.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtwjgsjymy.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gteexwjpsl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtnfkwtgxi.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtyszbjjmw.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtqtzyjjzy.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtzlujyede.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshakwxls.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtusmcvnmo.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtvidwqumq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtfmdzlior.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtuwykbqts.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtzscxuuug.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtmoptehyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtsmhsvwny.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtsvkuvvjh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtjdrhksmc.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gthdqsrbly.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtkbiodmha.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtumcdzcjg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtzxetjiec.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtfqhxqsgx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtmnefhkxx.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtosfxsjzp.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtoosigrux.html


<!-- 参考信息 -->