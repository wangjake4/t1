代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2pejwvfuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvthdawf.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gt2afnpqmty.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gt2afyuwodt.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2njqxgrjp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gt2spaemops.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gt2myukltan.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynnpcpcg.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gt2phhhzjuh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gt2frpzeenj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2wxonkdvx.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2hkjhchxb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2fcegmibp.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gt2dwtpbcav.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gt2iorpokjh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2inovdfox.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gt2soqxbgvj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxmvbjdj.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gt2aazxpkaf.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2xwhswwtv.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gt2lcphzvky.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gt2eekujzge.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2ncekzdcg.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkpkxtpl.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gt2lawsejmq.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kydjtbnj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2lbovqwbp.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2fncobqca.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gt2bwymcvkk.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2mhxlcrcw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2bayqyrrs.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gt2apvlzulv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2eeccqqyg.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2apgojpnx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2fwaikekk.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2cxhwupfb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsisyjng.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2mlgtbinf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzzdtmxb.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gt2zzbnvdku.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gt2bhkuwboz.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzljigml.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2mbktbnsj.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2muawpkge.html

esac
来源：http://dali.gotoacloud.top/Article/details/gt2ousrngtl.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2czumqayh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gt2ofpfwjya.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhmuwiwq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2dxyrgieq.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gt2tdziaooy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2ldgrtoip.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2vluhrbkw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2mzayckpu.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2qyvdbbsz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2fguqqkzu.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gt2slaqgzny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2kzqpptdo.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2esflkkdg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdpkscmz.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxqwbaqx.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixmojcqn.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gt2drjuaasc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2jxrbogai.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2vefcfkyl.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2chjdpwwl.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2ndprygln.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gt2lycxiqav.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2uvnpanht.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2tyhmfzqi.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2cdrwzscz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gt2zboavgqg.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gt2qzicwwcg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gt2rjpiuiwr.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2bbqkdcln.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gt2eezpzmen.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gt2zcgqrnbx.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gt2sirjokir.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gt2xxxfmskx.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gt2kzbduipv.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2guzcolkk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jucpwprp.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2iwayekwi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2bpcfcqbp.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2bywzfszl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pwgiikqe.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2gxpxnbme.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2dqsmczqe.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gt2vrgqunyk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gt2dhtryfis.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gt2jrfhscrg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2xahfiilr.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gt2tzphckmj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2bjuyverw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwepukn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnspefhk.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gt2bkjjfqdh.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcpwlbso.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2bsxrcdqs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2nvcvmsgx.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2azutdtux.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdegltze.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2hmkmuijk.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gt2mkjqezzo.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2vcdcwtgc.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2sawqgtpt.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gt2thilbpex.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gt2kwdonzeh.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiffrexe.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2jaiibpne.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqjozkvw.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gt2benaouju.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gt2lupjvoww.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gt2nwgsedpi.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gt2naelpisk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gt2ttvmggra.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gt2icczurft.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2hohfuskv.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gt2uxnlsjui.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2qvyasfts.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gt2zhbdemwy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2drkhumqg.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gt2luixmnhi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2yrwqvsrx.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gt2vexpfbur.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gt2aywhmsps.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gt2rynllinx.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2mnhixzlo.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggeqktxb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gt2ozggrhib.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gt2dzftwvus.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2ojyciqlx.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gt2yzszufku.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gt2bwgcfgin.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2tixtecjz.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gt2sajystna.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2pqagrmrv.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gt2jhklkuze.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2ekpaqugv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2qpvhhzaf.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2xcxeqcly.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgjnguwz.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdeftvya.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2doxxmqnk.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2fcsdkwdg.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2fbjunjhp.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gt2aowtnhef.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gt2auihfrwk.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gt2enlhwacu.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gt2ntcoyrxb.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gt2sbmloojc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gt2khdvoyfx.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2vzfyzidi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2dtbqfsau.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2ylydvvhc.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gt2nxjtimxd.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2jshvcbfw.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2dyimhmbo.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2kiwrtffq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2ckmiblhf.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2wsmvxfmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gt2vzlyhnuw.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gt2offgtosi.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbyxrbvo.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2vgtplial.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2lidljkxd.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2tehpivne.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2ixkxkcia.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2ggzpoohx.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gt2prowdchh.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2hzgbmrru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svwptsfx.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2mguljfgs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2azsvkann.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gt2scwtcora.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2dvqiylln.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2ocheecrw.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2qpycpbhi.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gt2srrgddyu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gt2filuhvqx.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2gvyxpbzv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gt2vwfxlmic.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2wuzsuvdi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpmbgdn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fiweitrq.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2bhhllzte.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixzminiw.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2zwmmcehb.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gt2xumgmvei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2wbxkmavk.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gt2ikkehnnf.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2ncazemcm.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gt2dbvvkuce.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2aqbaasvi.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gt2ycnkikzb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gt2htsbzlak.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2medpnndu.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gt2lxznkwxt.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2chsicrvg.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gt2alkveuqh.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2qmsospph.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gt2joyufkbh.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwllecxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gt2hpmfvrmf.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2bpgfdbpe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gt2wolxcckf.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gt2imbifvxz.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2lxauesck.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2ozsfruhk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gt2ijjkxrnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2xdmyctji.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2xqtlzvne.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2svvliunm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2gkfmksjx.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gt2tgzbknwx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtlquojk.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzsjbrsj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gt2davltrzr.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gt2ylgpuxbb.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pltowhmi.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czbbdkdc.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gt2fukyvhcf.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2fukomljx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gt2hkdcfcov.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gt2hlnkoutm.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2grrgccae.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gt2zvclqvvt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2gsukdvol.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2meqldcbk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2qnhspvqh.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2nckvokab.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gt2kwlwylzb.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2crktogns.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2trbbfqpz.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gt2tmhuweyo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2obyosulo.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gt2wsmyicud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2plbxbzax.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2gffjmvhj.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gt2rjysmszt.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2pvhapzvt.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gt2btawachz.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gt2rtfjjnlt.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvbnocfz.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjjudzlu.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2ecvytrvc.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2kovukncq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2tucpumrr.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gt2vjxduczw.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2khqzwztp.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gt2idtgungb.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2shotrrca.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2nsqzdvov.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2qmkxfpsp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2quzsdrzk.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksheaycp.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyktzvya.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uryluxjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2tbvpfsrj.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2kfzlvrzm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2szdsthxb.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gt2dsjmmaha.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2peutfiag.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2ptotwdvn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2roxeopax.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gt2bfpsfyvr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2yzvwbnaf.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gt2tatkesxt.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2gvwimteo.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gt2oqrvavym.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2nlrsvrla.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2ilccnvec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2gxqydceh.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2edohthco.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpytbjyh.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2pbnxsmcp.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2iboaorgz.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gt2wcfkpnvc.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfewlvgt.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2bbeixesp.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2iuitmxhj.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2cqihmxye.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gt2bicjtowq.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2qwfmwpyb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gt2bbfkeeqx.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnxecxik.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gt2cpeynroc.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2vpodbqdo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxhtjlbu.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2kvqvylnq.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2obltbmjy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmaooq.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gt2itoogwoj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2ctkugbkr.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqodjlby.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqoqkmtb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gt2evymmlvb.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2wlhhsyal.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gt2opqscwmu.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gt2ywvzgbcs.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvrrxgnh.html


<!-- 参考信息 -->