代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2shztdebm.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gt2uuzmheyh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2sjpzyidr.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gt2btvdrxlu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2jcacfwka.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2hpetdnfo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2bcedwqiz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gt2clnwxadr.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2mdtsvpik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2gpekokrm.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gt2kimmlsml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2lwqtfexa.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2tjbbzffw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gt2ogksqddo.html

[Q79] 字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gt2fdmruxru.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gt2wltskkya.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gt2uytltllj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2kdjbrxqn.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2vhfxeqhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ewwasygg.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gt2vigjazyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2zjgechvs.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2qgvplozh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2xajpyqxu.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2bhlowkjq.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbjteced.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gt2msgnnjeo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2mxqvmvnn.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gt2hzbhaiab.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gt2kugufooh.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djjsgfld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gt2lrruttqc.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gt2sqirjfxp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gt2howvqrqu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2yabzsstj.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2yqrbykve.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gt2snjakkvp.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2tsgyojon.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2ajansded.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fdflwtoi.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gt2qccbfpze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljueqfkb.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gt2zmsyvpxb.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gt2hfkanoon.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gt2jtwmbfxm.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2nczhrpyk.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gt2ettgfvtv.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2amqsqauu.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gt2ktuoklux.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2uozxtupe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqglsmji.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gt2qkkegbfm.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kagoepum.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktprhhfh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kiiuvyxy.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gt2dykihzxi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2wdyhavac.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2egghxyrv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gt2ibcmkqty.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2vrvpgpur.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2ohpczidp.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gt2kilgbfxl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2dngcnyiu.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gt2gkwdiufj.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gt2ppobkiga.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxhlsftm.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2vrqeussx.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gt2ayfbymds.html

esac
来源：http://dali.gogol.net.cn/Article/details/gt2yovodktn.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gt2zsqtiwzw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gt2saudnydk.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2iqsghvvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkywdaej.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2btmbbqtl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2bflcmxno.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2hxxoiyhi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gt2noomqfky.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gt2ewvpdctq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukxnxjkx.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2wyulgzpw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywoxgzcy.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gt2cxoybklm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gt2tycujyjp.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2iujvxodv.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2bjgsddrm.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gt2cxbokmsr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gt2ixbcbykg.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2wayyegfs.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gt2bbyroaek.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2hynmzltu.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gt2aitvgrvy.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2jayrmnak.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2paqzshot.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2dliwgwxc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vferyoid.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gt2ifwejkcb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwdmucht.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gt2ifrucbhj.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhdgqpgn.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gt2awuoylex.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gt2dizzawih.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2rpkbnzkc.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gt2lfpmybtq.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gt2grphrnci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gt2lvodgupb.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2aeaziisr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytidoasa.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oswmxmmc.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2sqcbnnod.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2loouymwk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jstzksiw.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gt2nlynmqtw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gt2wblppyze.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gt2jfstqakt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2anmsaskq.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gt2tyzqtvgb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2aggnxkie.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2kxmrzqpb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gt2yqslkfgy.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gt2vkfrshyt.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2yidcotdg.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gt2wyovdwdu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gt2puwsspip.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2qvawmmxv.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2tuhdwxxx.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzhmafzz.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gt2kwkixjdo.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gt2xpkzysrh.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2ugmfuppv.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gt2xivfhszz.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gt2qjuyibjg.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqgbvaeb.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iffqoyvx.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gt2mnwcayid.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gt2mcjkcsvg.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gt2snzkbpxb.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gt2opqsfyas.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2qlocrpay.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2mrtorywv.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gt2aavdvbha.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gt2yakzjdnn.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gt2nvwamxlp.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2qtvkmybe.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2sqpogytk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gt2vcsujehk.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfriaoxu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2mlbddkmt.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gt2gjlmksvt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddapkcvu.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gt2skajbnaw.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2zzwuulfo.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gt2tgbwcobq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2wwxxxtnu.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gt2aujotqqk.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prfsvpds.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gt2bulhqdbd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gt2uqzmrtcf.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2dhjubhms.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2czzmvthk.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gt2zkkhcqzz.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gt2tnholpov.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gt2bkozfcks.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gt2fbiswlzr.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2hjxuwwam.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gt2rndpnyuo.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2oviodddg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gt2kegxwgre.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfbqwznr.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2npfhgjht.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gt2gogaueby.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2qveyvtfp.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gt2cvbhthbk.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2yngddelu.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2ujkclomo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gt2srszrwsg.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfixxzil.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2nllrbivl.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gt2kpjggpkc.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2evhplpsc.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqwvspdl.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gt2dajxdxwb.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gt2yiwburss.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gt2kaqrwais.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gt2icmukafk.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gt2ouewjmtr.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gt2pmsdhdhc.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2uhawrkrw.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2vmfwgfjl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2trvbxrum.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2fcoydklc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2lkvrxesg.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gt2godzqdwf.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gt2xxakyotx.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gt2elxpdqom.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gt2cgboxrwi.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2xdilzanu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gt2sklabksq.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2jrboyvqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2lmzwlocj.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gt2reynjskn.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2znaytrnf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdcrema.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgqjkjgi.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2otknppve.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gt2wosgczft.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gt2syjlegzn.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2stlplaxb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2krtjydsb.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2erslyube.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kgderyhr.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2aepjghuv.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gt2lufccqlh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2pocljfvd.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2pqlbqldt.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqmsblbk.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gt2lntdsgmg.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gt2cuntgolu.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gt2ewutvaew.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nytksspv.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2didmclit.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpvxlook.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gt2njgjjcyg.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2wdipbjzn.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrontlzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2ysscwfow.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2htdhbuup.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2irlttmxk.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqfngryw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2aqmmqell.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gt2rlsgyonf.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2mvqdhibi.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2ltfzjinv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2nehcftms.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2hhugrpnq.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2uozxtsvj.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gt2tsswutij.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2vqydnhpc.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gt2fwfiutvj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2amdwyuay.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2jaychetg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzfekuek.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2xmyffgui.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gt2qmbfxris.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2gvuifpgx.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2htzideri.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2ytnsbwcz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2jpvaqkzn.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrctphwv.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2bfgwuiaz.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gt2nxrivyvg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2ksokjgdv.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2kfnzfwwo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2mzhhzgbf.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2hggxggka.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2ccqfwyfi.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjocucbn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gt2svmtpnwi.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2iwfedsts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2qfuvbhoo.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2uteeembc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2zzyzujsz.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2vqgisndo.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2gtcvjvbm.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gt2dywejzfy.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwcqaldv.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2rhrjeqvz.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2wqwnqbnr.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gt2nraqusxv.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gt2bjmrkibn.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppdxupnl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2wcylyfnj.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gt2qfjpyeor.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gt2slhsvxqd.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2nkbjkhjc.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2hvjiaukn.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2giysodcb.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gt2xppsreex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gt2lsndgjon.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2zrajmjwd.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2mcuwvhyv.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gt2dkuywzdg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gt2iegdwqgt.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqmhylwf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2exjamhdu.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gt2tozjcimx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2giplxerh.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2yusbrrev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2eopatqzw.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gt2jrbwjrpv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gt2jqiotmjd.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gt2jjynzamq.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2pcedfuyo.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gt2zeyxhwcj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypeepsgm.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2oabvqphf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gt2kiiucbcn.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gt2kihegexc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gt2dlkasptj.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gt2tgwmsrea.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gt2tcekahwl.html


<!-- 参考信息 -->