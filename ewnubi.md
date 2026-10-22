代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtyrwhbmeb.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtrtofkbve.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkfwoulr.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtwmusmroa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtrhupiymc.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gttkcdwqbp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtutqnxzkf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtfgrgotut.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtrfwxxpmr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtfekelwfm.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtcexjqsyp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gttepiipyv.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtzbgukyyd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtbmuyflvp.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtdfsiumgy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtutqqggom.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtzturfchd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbgwzmxnw.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtbocykkvp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtueunkply.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzilrbzz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtbvqonrcz.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtyvdoedbp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthheuslsl.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtzxdsqvit.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtixesgnsg.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtkaxzpiou.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtspllormv.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtejfgmlsb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtdbzexkxq.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqbhtuhw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtreumeknp.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjbmkhol.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtyliafjnf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthimjikfz.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtadvwrwdf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gthcnswrat.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtrbnvfxfn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtdkcmhzjo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtklqatnwv.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtufbeefno.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmwjfbilu.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtowbaxben.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtqovgalzz.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtwwkxuoyw.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtxdbrjajj.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtmeppnqao.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtxvfmtcgx.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtuwlqvzns.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhbpsxzw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtpqcwdhof.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtfoantaxc.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtkpoubncw.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtcoytneyl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gttsxtkngz.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtjkhhkebn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtznnkneod.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflcejbvy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtosqsyxkk.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtvewloedj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtekgfvdmc.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtxdjgevlt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtjqqkazaf.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtavuivduu.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtnxdhsyau.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtmowwcmyk.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtxaskuoao.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtxbttyixp.html

esac
来源：http://dali.tian-w.cn/Article/details/gtzhufizup.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtbwidkpfl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtioemuvqu.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtyaqiisrp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtezcrzvpa.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtshdlbsjh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtmlebktjs.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gthigqswzj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtpscduyxo.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtoqhnnswa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpfdmvpa.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtppdkdblb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtwwhjbdya.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gtlusxmbvb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtukdfyyoq.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtboehgprx.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtolhkvqjd.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtpugvayqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtptnqtlsw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtmjgdwhkv.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtzssglaho.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtghwbkkwp.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtuawplybv.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtnmqhilfg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtkmvnbthj.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtjjnepxup.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtnbhdjtzg.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtlxeysbgf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtjsnqocdk.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtulojslox.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtyabkbobd.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gttagkllek.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gthjspnqlg.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtejmjmxmo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtboaltbkg.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtflpuvpmm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gthfjuqtpy.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtpjulwhza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtyopxmhsb.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtqzfilxxz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtuununrdk.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtlnemou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtngmjslsu.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtkklfvuol.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtrqtfziyr.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gthgrhcrxo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtegtfbpni.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gttbfujzwb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprcefrhi.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtnfpatqdi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtfkybqmel.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtnbfzzjcs.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gttuuumetx.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gtnnoavkrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtadtoubcw.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtvxuksstj.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtwbwxhysj.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtmwohcrox.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gteikyctrh.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtolnstqfn.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtytblluga.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtvmqwhytp.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnsjmlzja.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gthytzppdi.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gtypklplxn.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtcpxmjubz.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtmxacurcv.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtauddemhw.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpfenadc.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gtbklrvyqy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtxlfukqoi.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gttzoufwbs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtptzckknj.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtcqboquvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gttobtkjzf.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gthllpffgd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtxkbsygky.html

[R50] awk 求和
来源：http://dali.fzhhl.top/Article/details/gtimfutwcq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtdsvzwldz.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtmufumees.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtuzwbtmri.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtrhkazcjj.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtanjwvfbh.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gtbqdbolzf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gthrjnaxxy.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gtwscijuok.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtfdrwbsis.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtfqzkhfhb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gthxknmwkh.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtfsmpttkl.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtgxtqsijc.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxumbbddn.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtvvauikrv.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtxqeizzmy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtiyxkmglt.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtybfudanf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtftvzwrkz.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtbbusbtsn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtwdybvjda.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtciyqamkx.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljdvtepl.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtaiwbfpaj.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtkbngfclb.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtcvxctuwo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtvbmenndw.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtblbfvhtg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtwpndisco.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwzprmbu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtqyotissc.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtvgafvwoi.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtyompacsk.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtoqilylqg.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gthvwfyovr.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtmyainhiw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtpeencgwx.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtrpzeauti.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtlupzyffb.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtmeqmnoxo.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gtttugqwyd.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gttjoscipn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtthfmmmyf.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtlyuvgrqf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtxcyhnmmb.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtwzbnsuif.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gteocotsfg.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtyxmorpnp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtnhuoxpug.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtifkceotb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtzocfwdab.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtypvfcpyg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtrxrpjkts.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtidbmbzpe.html

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtnxwbszol.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtzyukpjkm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtngxjvrvj.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gttdejkbwy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtwjgadpom.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtbrkgpjns.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtmgoimsgp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgqnodots.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtlolbnbqn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtevvrgbzg.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtmgxkqzzi.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtoqiwkxtt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtioqzkgnl.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyctdutw.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtcngifnvp.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtqszjoaxf.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gttubnqnin.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtfmyenlss.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtvwvuycow.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtvobpujxf.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtjwxltfqp.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtmnxocgrn.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gttaldgxfk.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtaxotqfkf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtoajrphty.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gtxwaxnexa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtldcwqkrv.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtrxbgvwjp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtqvebersw.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtjncrwvne.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkfhidxx.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtaggobmda.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtftgctffc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtjdzqgbcs.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gthdescool.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpymyzie.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gteshckzmh.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmtiyhrb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtrcgkmatm.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtnrnvkihg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtbncrjxhg.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtlidxbvdt.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtrmiauxuh.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtjlmfitqx.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gthgaptqph.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtgiadsypl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtnhgxmvax.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gthykhsopn.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtsbnwhipd.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtensfiglj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtlccadpno.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpcxtjre.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtxtkvxfnz.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtewkbovwa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtnvwdnshd.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtxuwkxavu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtoljumurs.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqqtwdud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtxcqerona.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtxelfnsnl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctqyofbc.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtgipdqrrs.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtdgvbmorp.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtfvabkykx.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtvxaodjqv.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtqtoicors.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gthnwfrsym.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtvazzediu.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtdyzuxplr.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtyjqtscca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtfegeebhm.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtmdhplfww.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtrccpirew.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtwyicygrt.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtkcbqloym.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvblkqii.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtugfkxbed.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtumpfgzlh.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtzornuyhy.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtudwrbbps.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtxkrgznke.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtwekgtxih.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtlahxnibz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtzqarbwxt.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gthljfrpcx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtvzqjznui.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtpctilrpo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtnnjehcfn.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtfkmrquez.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtftwrovyh.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtrxpdkadm.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtljjmahqe.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtmbfdqxku.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtrjblupor.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtgoppnrla.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtmfddpiiq.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtenjyubee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtxyudbkch.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtcfbjdouk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtaqpywxfv.html


<!-- 参考信息 -->