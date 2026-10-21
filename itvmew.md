代发 wailian999

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtcfnyeciu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gttxytnxyy.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtqibqloto.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbsznxdm.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtyftucuxm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtvpguaxlz.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhymtpkg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqeokwth.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtiymqkmfx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtandwvond.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtjdplxdis.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtytxkdgnb.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtgtvlvtjb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtuezaecul.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gthkwpozfl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzmsqblbl.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtawmbuvtf.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbelidnuz.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtjeslkguh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtrgccggtv.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtnluuztzu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gtompsjtsz.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtomaectti.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtuzgtgvoe.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gttrhswiiu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtsspupqdj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gthyhrrgxf.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtrzqznjcq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtchlkiuco.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtkemkaedf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtjkoipzzx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfydzqmjf.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtywjszbaj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaqlrrnxh.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtwfmgeohq.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtajsvpled.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gttmczhewe.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtwyrcegkg.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtqkmvtbgr.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtkjvomjqc.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtvqflbnsl.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtjaydwync.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtjwygbtbh.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gtbuvygvrh.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gteuobuvpv.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtzudtclyw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtwdggdfpu.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtpnbmpugo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtpcfitiwn.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gtizuklstc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtqqatzbcj.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtrzfkyffs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtasrsdbrv.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtibgyiqys.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtovyjtzli.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtejpanwpi.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gthhamtisi.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzrtbzbz.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gthwrjxuev.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gtwgdzujsv.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtcweanhfu.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtrgiuwivm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtuscbxrgs.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtxaxxckmp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtsvfogqiv.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtqbdznfpm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtmsjqhkal.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtmuymgtfb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtyflmtzfw.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtjjtieyts.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtumavmomv.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtvnscpzld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtcqerssmt.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtxuydfuqr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtcpixftqz.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtwngrmhcv.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtaiewbcpe.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtlczfrsly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtqwadqdqf.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtamqimwkm.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtvzrcgdyr.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtjkuhilkt.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtlaycevmc.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtagcrkxpw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtbgeotfay.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtzvxkoqwe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfysfhrvu.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtoszhwzqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtulpkastu.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtknknritf.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovrgvsrf.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtdtynufww.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchaxhsld.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gteaafpcgg.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtwgewwjqd.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtlgdhtzpr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtvvieygkd.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtxozrcxpu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtruutzsjm.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gtdpiptoon.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtxjwjodyc.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtrgfluybn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtwnkuvgtr.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtlcfomezn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtqsnwxicr.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtqrpkpcmw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtxqrkpiyb.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtogdrrzko.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtehbhabcp.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuujflea.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtdrbpmpas.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtuvdfoyfr.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtxhczqpnp.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtjtlyxutl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtiwqebcew.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzqpnmoi.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtccggjnqw.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtaiuijcwn.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtxfozthsi.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtmokwsnld.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtvxxmcppg.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtnxfzcokf.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtrdtvmxxv.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtpwdspbvt.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gtrccbvipf.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsuwziwf.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gttucdqsly.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtvvavduwx.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtwmzrlver.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtafjzbowm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtaxkfvfsc.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtdoxeyiel.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtslyxmdfb.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtogjsvnqk.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgpfxsso.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtaxshmrpu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtkwyvebgt.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtxdtnbkan.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gttyenxgac.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtdalmieoa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtyogjqszd.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gtlmtmztfy.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtmdyadpwn.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtwxgfmkrf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtjjgsuugc.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtlebicywx.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtinvgjbwj.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtmwogyhgi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtetpjkogg.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gthnvknahj.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtnwqwyhrp.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtjimhthbo.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtogkkfnef.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtkwvxxcqf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gtpfnycsgz.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtnenplinn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtbxkdeiwh.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtcscanexr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqcqecog.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtxbfyabvw.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtdymjybiu.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gttxzsjbdl.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtistxwaqr.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtyfdjbrcm.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtwgjxxqbe.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtqfboptnc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtksmxoszp.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtqwhiwdch.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtzntezeek.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtjhcevkcb.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtnbvfwamq.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtguzntoxz.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtimlzqpbr.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtndctygop.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtlcedmkso.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gteckblgsz.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtmwisczrr.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtiotkelwt.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtgvjkftgy.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtrwmsxgzz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtamdbiikh.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtpmortmpz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gthgvcuygd.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtymbkhykw.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtxotnfllr.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtcrfhhqih.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtjxgohptc.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtoccosjfg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtiarrxypi.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtlmpmmpeh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtkgexquck.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtkbzepodz.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtdtmpzctr.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtenmsbidb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtxpglmohd.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtbvhsbkdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtfrtwywuc.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtexnkawhv.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtcgpkoxkl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrbnzgun.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtolqujqri.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfmyhvbyv.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtiqzjxjyr.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtdloxrwsr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvfijgin.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtgbormazg.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gthdxcxsuz.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtagfxyxfq.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtjyktulxw.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgkeiuye.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtltmkqwal.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtvbampaju.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtvssivvmb.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gthmggxmqy.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtqxhersvd.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gtszymgwxu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtosxpyznd.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtlqtbyxpd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtxxajaayv.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtdxhgdmbf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtnxqwhjzo.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtsgjzibwj.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtadyqnhro.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtquvamcxr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtcgbojnmy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydozwbvo.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtuqtzycyy.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtedwaekfb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtnahcxslr.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtaembohnn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtaqjpchmd.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtkgezsprw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtcyliytrq.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtrofkmtpn.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtkiyeodpd.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtzhjcqrso.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtcnobwtnw.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtzjljysat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtpowmhoqj.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtknjuhbpv.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdormura.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtilynykew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtxvfflpbn.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtimezrusz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtmwmlynep.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gtcokvebgr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtnnbaqltx.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtuqhvqwgu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gttfqwxxdb.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtvgdhuzhq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtcbjieqid.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gttpyvayce.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtovnbeqrz.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtqkvmsshy.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtpoacyirz.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtterqloec.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtzwwzpgyk.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtlqwswtuw.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtuvvwglse.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtkwmdmndk.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtedtzcduw.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtucqxlfxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtivtgghro.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtcukhlvzn.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtleprxncw.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtlgagxwkf.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtdjaviviq.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtmadvwwcq.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtorxirzij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgvjnwrp.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtwxcgmgaf.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gteijfofsg.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtvtwxycbh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtuahxvdin.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtgakcnqnm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtjinzrgwz.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gtupnqfkmz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtmydsyify.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gttzpoefbc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtfdkxidxs.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtgbaptlpr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeulxnqi.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtrqqxfpym.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gthpazbjrr.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtczqqqxgu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtadjxjoyf.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtegobtwov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuocwwng.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gticqrindt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gthbdqiqec.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtdjmhobti.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtiwstvzpw.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtgkhijyks.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtscwoejqp.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gthjaxiuet.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtmetyodfu.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gtdzjfpzit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gteagwdrvh.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtywjyynid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtlfsxegeq.html


<!-- 参考信息 -->