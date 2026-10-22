代发 wailian999

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2abimpcup.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gt2dnppjqfm.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gt2urtmuteu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2xffyqrwq.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gt2jtyhbuux.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2wksmsmyj.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2yxrqrfnh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2dkdpxcbd.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeagjbyn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2wuzwooor.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2sundjiun.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2ehikaleq.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gt2ommuagtj.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2eoesvcsh.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gt2igcifepa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gt2ajhilcxu.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gt2ibcwafqi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqhwpkn.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gt2mhxcwjda.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gt2tlqixtyr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2capnfsmr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2fvnkodbc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2gassqyvk.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2saazqfiz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2pdoyuwcu.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbspbkda.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldudmukm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qxtrynjq.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gt2ekdlrhhl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gaiekgmb.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gt2saptaerf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2atkkdqtb.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gt2rsqlnwif.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gt2jmvuhvpr.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2xztpxpii.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2ypruwizm.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2hjekptvd.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gt2xcxdilwa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gt2jqyvrxfa.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2jbjywaex.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gt2vrgyvqnl.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gt2qhvkhsem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dnuoweyf.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gt2vhuivplu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2emrmttmg.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2wsohnqkj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2nwuvliaa.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2luedsian.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2phcgrbep.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2wclscksq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2whxxybxl.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2ohbcvpdk.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2lrvczclp.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2fxmzqntr.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2nqirbemz.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gt2jflkvnmi.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2ipzehiyf.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gt2qxcztylp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2tavsqqvw.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2mqeftucv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2zkttbnvq.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2ohkmuetq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2twjlovzb.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2hptzofkq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gt2flkldkvj.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrztjxpb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2ffkskvta.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2vzvwyizc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gt2moyogqaj.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubnxjkid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gt2bacqecpc.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2kthcbuxb.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gt2xmutabfw.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2nakmmcwa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2jbiebzbl.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2cnmlzxah.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gt2pwunsugy.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsyychev.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gt2djnaknym.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2sfrfjnfp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2zxprwetn.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2mceiqtho.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gt2ncsvchqq.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2gshtzzji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gt2szpbmelm.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrrqlgwu.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2fkvrunnq.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gt2prubvkyn.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gt2vcjeueir.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gt2hyrokbzd.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2gvmgvfiy.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gt2ttwvqrvz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ewohnqxp.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gt2mhwredfg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxxgrxmn.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gt2ottrqcsj.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2cfezebkg.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gt2jrjksvus.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2ijfjnfup.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2pjwbdzeq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2ktmrlkxn.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2xtfftnpg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbkdgijv.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2nqrwrkng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2vobabcec.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gt2gtqyboec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2aqmerfei.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2vfkfpody.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2kcxshuaf.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2lnotwndo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhigpzdv.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gt2nbcyswsi.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2ofgqddcx.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gt2nprydgyc.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gt2vcccdklt.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gt2vlwcckbs.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2mlhggdzm.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2cdntlhtj.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2vvuyzcak.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gt2serzstfs.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2lcfusyoh.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2ehuzlsub.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gt2klwcourh.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2efdpwewh.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gt2xxnbanpm.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2azccpkfw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gt2kxashkhy.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gt2iwdagtcq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2jtcfshlr.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gt2sxregdvv.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2faejomke.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2qwssirnn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gt2gzdbsunl.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbcqgvjz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2lvnpblpm.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gt2jjrmetky.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gt2lezarkfb.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2mlonzkbf.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gt2nxacoepd.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2ezfxrzzv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtoruufz.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gt2geshiwmt.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2emmlngys.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2vackzcpd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2sceupqdc.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2bberslah.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gt2rzbfzjuu.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2czwekdhw.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2jfpbtllt.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2uoabywbu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2obkvjerw.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2qzhvoghp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gt2wukjihub.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2sbpavddj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wonnhflb.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gt2oaixbpjr.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gt2ezgzugwi.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2erswctrj.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gt2lzzrbcrl.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gt2cneppnug.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2szixvwtq.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gt2rpxlbcvw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqtypujh.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyaelkof.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gt2ufkgumqw.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2obzlotxg.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2hozuvepz.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skzuvshs.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2rcobmcgn.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gt2ranolicu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2habgzvkl.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gt2kyspnukb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gt2hdehdypu.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gt2iifrdfqg.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzjabjwl.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2rvploevs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gt2cpxduinb.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gt2yxzsqfpi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2vcjykkiu.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2dlcswyeu.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2djaayyxq.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2blovacge.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2uubfokww.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgwwjxvq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gt2uuynpugv.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gt2qqmvppum.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2hqrqwtft.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gt2pludbhso.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gt2sxdtxaou.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2jktquzkr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgfeswki.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gt2tpvbaomq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2dueupbnc.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2zghqpurm.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gt2ljzpnrnd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqljrgbv.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gt2vemkhgyt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qkabgpcv.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2aeuktodw.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2essslfao.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gt2lrmbnsij.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2rpenxshc.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gt2ppmhdxxh.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2ajkosnbg.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gt2bswjmfbr.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inhlsrpz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2bfwwsjri.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2ndhciprg.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2vknfniyi.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2sxwhahah.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gt2jvpszcho.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2gwhyxanu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gt2qdhfqhtd.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gt2omclidji.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gt2wjmfimns.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2yqiznahg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2cmqnlbrv.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gt2yrocszru.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gt2xzgzsutk.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ocvmctte.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gt2mulrnygi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2ydrnfkil.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2fghpfvom.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gt2rkqiyfsh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2emsaafsu.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gt2jegwyshd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gt2fakspjyw.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2mbwpnfgu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2flabaspl.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2fcimvpce.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gt2wjepmtot.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gt2lbniared.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2ayikauoi.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2egfdrdur.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2oqtuzntw.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2wussvbxo.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2jpudtszd.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gt2xktpbqgc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldxfdjkn.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2lbjisgiu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2kocmbyev.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2iqhooheg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gt2bqmntsan.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gt2vuvoqlbz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2ruaogqob.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2cbcbvebh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2uxietbmg.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gt2unuccdrc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2crwdygbr.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gt2zrzmreiu.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmdczzbr.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gt2yeieyilx.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2rxbmpirx.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gt2hrciywfw.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2clifoeha.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2cemquwnj.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2dsnwdgqa.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2qksrtajz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzqwctra.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2wdiqxtcu.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktwvtett.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gt2gmzxvrzw.html

#endif
来源：http://dali.daxiang520.top/Article/details/gt2rwnwgast.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2tjjpqalh.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifagywln.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xitxdcuo.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2cbnccifc.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2eklpszla.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdxoluky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gt2bwconjai.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gt2kspqxtjk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2zeigxaqp.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2pdefttme.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2lrinxfbr.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gt2sodcukbo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2tjptkkpf.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2eiutlene.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gt2xuehpxff.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agoytcsf.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2kdfvcbjw.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2ivcssprt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gt2xocasdpi.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gt2qfqhmbtk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2ajpwxscj.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2drdcbuya.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gt2xfthsysx.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nejcyryp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2ybsbchod.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gt2ykaiolog.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2trwijgeh.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqwxgbrb.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gt2knhnejed.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2ddscoadm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2snturrnc.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gt2pqugmxot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gt2ieenhabr.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2nowyfpsl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypioujhd.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2sedhztlc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2hxqdhivl.html


<!-- 参考信息 -->