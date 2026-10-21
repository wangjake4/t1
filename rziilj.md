代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtmzuzxflb.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtqmgdxfyn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gttumylkho.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gthkoahaib.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtidrmnapy.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtlbggfksb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtgiogfozt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtdjerqhrj.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtbgfsjgxk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtkivehblz.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gtvgdswyji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtdchnbdzr.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gtcqhdqxfe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtpgpxeovh.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtvgasfhmc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtvplymrqw.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtxwfcrsua.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtfciekrdq.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtudburijx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtesetnaug.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtjudvibzy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjvtdvcoi.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtwmdeaooh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtposvjlct.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtzymooypl.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtczabuhrg.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtvexskndr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtatwdeolm.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtlczxcrvn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtcfuyznxg.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtymxwggxw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtlsflwqfj.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtlmkaohpr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtkgffiivm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtstdnoztq.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtrqglwyva.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtwfkclnyj.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtadqxscow.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtodqsibht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjcjaqeqk.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtnbncotsh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtguigzyhm.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gtcitnttkw.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtkzlhyfyy.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtxqqtzkqq.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gttobvruel.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtbrrxnuar.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtuarhcrrv.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtsqrcfxkc.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtousvwola.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtrbcnsdoe.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gtsixixibj.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtofturklk.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtgtqarvjh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtwegtapwm.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtylldbokw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtlbjcfuqt.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtjoupqdea.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtsvumwoxw.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtidicsevi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfvmjxrol.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtnzfhvxbv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtwngozcdo.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtibyrwjss.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtfvghegmc.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtbmkjfdyn.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gthqrxsfbg.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtwtvywybs.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtwkiwmmtl.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtordvidzb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtwzqtquus.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtwztyelev.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtanannojx.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gttcyaxchf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtehmeodpd.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtkndrikbt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtktbpdtin.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtiyhuxjzz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtodmctgwn.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtqbsosxhp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtiqzavvpv.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtxljwnnsg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtlewwixxz.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtlqjdoedf.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtbqrqpula.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtmzpehbhq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gtufxmwjiy.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtjghtgjiv.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtreslodtt.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtxialhnsg.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtivduzeck.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtjajajmmk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gttndtrdeh.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtbiqbplcb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtocigrfxr.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtbeuhylrz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtpqajgveu.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gtawiptgbx.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtrmkogqfi.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvudlcjn.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtjlrlpywq.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtyoxevfkv.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gtyzgsfosc.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtogxnkxcr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtpfaxusqp.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtvxibfmai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtruqvqhbw.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtgjkxocon.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtcwenooxj.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gtwgpepqxl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtrvkkovnp.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtxisgdwnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtaaajmqhj.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaencwwga.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtfaentcvz.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtaehdrgtt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtvfsvrdso.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtjzikajsj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtehiebapc.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gtmcqsmmta.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtfuhrehtm.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtddxxomgp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtwpkhrhdr.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtowxrqwsg.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtrjlwdtzd.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gthuxwpirj.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtuioxbsjv.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtpahubtoe.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtlqygqroy.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gttxqygqfq.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtlwuebjyt.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtcqeubpuu.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gttxxoohyf.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtfyqitlsv.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtqzgqdzfc.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtuvjqbkaz.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtntyyphzm.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gtaoiqkhjy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gtvsilpkxw.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gtscmkyyxe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtbbdpvxdr.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtncsjbvvd.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtgvmzomzz.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdobexnrh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtorpndktz.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtpzmfzmpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtpavzogca.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gttdirlici.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtvuwubwwc.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtmtcasunn.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gturytdbsn.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtguwzzzjp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwzasvsp.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtwbjdujef.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gtbrtpnfot.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gtluyguhzf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtrkdnxsuv.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtgdpyevut.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtmtabnube.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtpgcdxbpo.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtaunwcwct.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gthvcyhcnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtfseyugfx.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttydiwnbe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtydlvqabi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtoigjdmkk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtjonwicmf.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtrmlrwsdg.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtzvxjubhs.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtuzmhpeez.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtrwoanjng.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtufradcki.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytrggaag.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtlakolamu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcmmfwno.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtxqbvolpq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gtolgzmjfa.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtqkbnqrom.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtspituzhs.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtybqrdniy.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtwnabkzhz.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtxqijybsx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtcdbfueus.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gttwbpptba.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gththvwons.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtvipgydjy.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gtagzfxgwc.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbugkkbqe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtdzegmgos.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtanovhneq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtdrbnimlj.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtjsxffkos.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gttwneynsa.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtnxxkagnt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtfedsyplz.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtollqufgf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtqvzzykuo.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtgubvnizc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtuhlnvnet.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtkuifxkom.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtuwtezbvb.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtozsdnlfk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtykjjpugf.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtiqwhaqxb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtygtiwuhu.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtswllrfiz.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtlrwuzppp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtohiiefex.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtiqzppnbs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxgxizwub.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtonigqchw.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtczgkvdgs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbwvndgqn.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtjscyiczq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtmitrgovt.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtnxacybxf.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtgcahabtj.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtxmvhyekc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtfhbovbdt.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtbtgvaalo.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtgdjdmdra.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtumkukrnc.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtesgmvthl.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtbicljcrc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gttmolxaea.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtbnlmrdgi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtrbakwpll.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtyetfiodl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gthkoxcyno.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtlcxrcopk.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtmjdlflvi.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtaecgiypx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtlejlelah.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtalabhjkp.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtiytfaosn.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtimhfjxro.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtyvepigyf.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtucntiimv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtuaorsvxw.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtzyhawits.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gterglcyzw.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtuhfgbhqz.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gtqbmkvxhb.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtmnyczhpk.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtzfwrtuoh.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtqkuesnng.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtcnljbotb.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtlkvmvhcl.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtvruhbqnt.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtvtrzirvi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtcfeoffrs.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtgphojofj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtquelxipn.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtxtuasirh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtjodufboh.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gtxrcgnuxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gthyfupcxi.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtcapuqsxa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtjkwvsnjp.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtdtyutzyb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gthlpleqnp.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtryiqqtog.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtrzizzgjb.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtfevqhxgi.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtrzzdgwxb.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtzwxrlzrv.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtjdoblqwc.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtjrnxgpxi.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsyjrhim.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gteuqbujri.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtdgixwgbn.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtxytcaepv.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtpqmmmlky.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtgzoxqmbu.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtkqkcudmz.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtckqfcdjh.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtgwuvdjpi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtdssgcdgr.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtzqmqlrgc.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtcvwoyepb.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtgikcqfya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtdortelcj.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtltknwamg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtpnmxlabu.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtuvjerego.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtyqhwzkpc.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtufresjzz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gttgovqgxa.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtvlwclwrn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtxdvvtkqa.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbyhqygr.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtxlwzkftw.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtplzmbbrp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtjhkzfdvj.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtntzrynnd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtrvpbkify.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gthhfjhmcu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtwtkexpux.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gttrnctpeq.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtiyyexmiu.html


<!-- 参考信息 -->