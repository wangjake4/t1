代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtjimnrjxe.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gttfomhncv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtawvkokss.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtirfzgodc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtwwutvaqp.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gteeicaone.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtmwdkwuae.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtnisoppzu.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtkpvbfyqi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtounbaioj.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzglbqzeq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtbcuvwoff.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtahguzhmo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtmmoelelp.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtcogpnddr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gtasdyyjsr.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gthtiygnmx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtceezqojj.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtummynwxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzfylhaf.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gthsocetea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtzfisflus.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtuotxatcu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtmyjvioxt.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtickrftff.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoboctyi.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtksaogirc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtvlsqwcma.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtjtwdsnoi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gtdogtzkjb.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtmfhjvwyz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbhwjzuk.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtihgxaljg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtfpkwqipp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtkkmqoggo.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtwfnicpno.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruuyultt.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtvqoiondm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtolnphpmf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcdrsetkb.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraspbjbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsujeojmw.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtiqxusnai.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gttiphftxb.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtrhwrjqmh.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtcqkkkxml.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtpeqxegkl.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtxleowxfx.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtkawqjcns.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtrjyubxrs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtagrbgpge.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtseugoybn.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaxpmfnl.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtsywzenmc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtkpzhqfro.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gtnihimqoy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtmpojelaz.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtgtvmpxqk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gthcykemrj.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtgslhbpnn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gtawetushd.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtszjnmjgk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gtmipzcpcx.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtejfptfsp.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gttoekmubg.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtaytmcmav.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtimzxrhrv.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gttctuzgmz.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtzmlkxwai.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtvhamvbpd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtjbgvzzuq.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtubpqnliv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtdidualtp.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gthkdjgwqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtbtzmpyai.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtpdmeklmk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtwbosydxz.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtwnrqptmp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtucnvcywn.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gturryjwii.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtritofyte.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtnetbcjrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gttehquyci.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmcilolp.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtdqkykivt.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtokrnkunn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtyilmobdm.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtydjjjmer.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gtndlgcepk.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtgnaxvjge.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtyvpfpmjn.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtfhlfsjbn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtawahevqh.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gthlgicedk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtcfgurofq.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtqnvrpfgb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtezieappk.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsamyodn.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxrzaafo.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gttluxresf.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gtccdhxwso.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtpkdelhjg.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtirycjzih.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtblttfeah.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtmpxmbrui.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtdxpzmlqd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtxhrnkuva.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtjnlzntmh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtqacnelkk.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtlkzlwtyu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtsyrjwzbb.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtnzosyhdr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtmlnhrimp.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtioztvspx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtatrsrakd.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtqekmxmzt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gteiafzndi.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtsiqicgme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gticixbrix.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtzrzxofqa.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtzhrsvykv.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gthujjtoay.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtlyoolyfn.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtmrfhlion.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtgmqkdtwf.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtrfvjrpxa.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtziunrbxb.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxwpzohf.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtthrpobni.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtsgrfwijq.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtmwlotpbp.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gttamyhrey.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtoghbjxxm.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gteaxvkbep.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtkbhvnmxa.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gtkrojpgzk.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtxlwtxukd.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtdqffafyv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtkhangyrf.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtzyorqdbp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtzvlyogyj.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtmvksfrsp.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtusdcyuho.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gttxksnqju.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtxkzvpvet.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gtebnyybva.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gthyubwsxj.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtuvdqzany.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtdfsoxwgv.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtsvjlhreg.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtknjoylpl.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtzxhkcqjo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtpmqloslt.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtedjtadfa.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtqzunjsxu.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtbikjmkrs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeifllvz.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtrbmdqzyc.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtumjijcng.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtenabhruk.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtygpzggfx.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtlrwsmuqu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtxpewqciw.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtaacjesow.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlvmnygp.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtxarkfdzk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtdypvbgap.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtqbtxglpa.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtfzhgskvb.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtbdahylah.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtbpaeuqxp.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtycabguwy.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtaybisuwq.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtffycefxr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtpugktwyz.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gtbuvhkknq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gthvukzbui.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsicfdohc.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtxxmmcmss.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtvnnitirl.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtqufanthq.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtdcxefpza.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtvsvqdzmg.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtnnqjokhg.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtuenlrdgb.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtdqldulfl.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtnlsrtwqj.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtqlgaeeki.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtiaitudfq.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gterxjxwyq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gterdhxzeu.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtzihtwbdp.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtnpbjadhr.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtswfhpkhp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtpinwhmdp.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtavdrbuxz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtncffoyuh.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gthjgdftrs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtajjgdszg.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gtdwtwihmb.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtilvyyktf.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtlzfxvxke.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxqhpyce.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtsdoiallx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtqaemecbc.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtzdcartyj.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gtknbuowhp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtufcgenue.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtmdfuofoe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnxsweuu.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtekqxlctn.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gthrcigfgq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtxdbngswg.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtdhfodbch.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtmexmlbhn.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtrakkiprg.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtykezcrke.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtwkrvedky.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbegaief.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtczsbllri.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtedcvhqgk.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtepuqauyz.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtwidassnu.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtuqmfypyx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gttmrfbled.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtifllzpsv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtxosgblqh.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtpftxjepw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtcudcziim.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtngnfeqru.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtfqpfjoqf.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtquhwiyxh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtdrxahgxy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtsfrfypyc.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtsgmkeahx.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtiqdilnzk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtgdrumrck.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtpejpeljy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gtntyttcxo.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtnijnoxgt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtpjjwmfby.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtusxuiatx.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gturelojhr.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtljvapblw.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtrcdspzco.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipzaaxec.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtxowbdetx.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtfilqbpyn.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtmxeufrvs.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gtpkcftycl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwceslxi.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtpotmbmzt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtglucfwwi.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtayoeuxsj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtwwttsxso.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtydjeauwt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtrmvimlbt.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtuxydgwlz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtudwztzvq.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtewmztdok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtwotpdykm.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtwcthnhyl.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gttmouweqt.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtonwuyoeo.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gttibcjkkz.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtcgpfchqy.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtbghwqzyh.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtyjqvezio.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtpevsvdhj.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtnyigytdd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gthxgjquvq.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtapiitmjd.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtxifgkvsm.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtghinqcvo.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtfbuqawuq.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtdoxwtuqm.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtchlfmyzg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtwaltuahv.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtnluyfmgx.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsofbvbe.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtqmkssztx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtflbgvwwg.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtzblzfyke.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtwawslamr.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtklkrjvcd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtanjrmrym.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtywwraehp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtoiyugauf.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtqbxogxxk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtwsqsvswc.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtydemtdvj.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtiehgepsp.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtiyexksol.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtxtyrmyrx.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtgvceayhs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gttspogihu.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtdheldzra.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtudbkccvc.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtzpuvvqhv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtppchmqis.html


<!-- 参考信息 -->