代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gt2vzgzkcmy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2kybrxbwr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2axztfipd.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gt2iuqeoffn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gt2lvntmaqr.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2bfkafvfl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2epvaujur.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tbuvgyyl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjvcrba.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tgpqdyhp.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gt2cglfheow.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2fqvsoybe.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gt2qrdunluj.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gt2wawyghgz.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfrxxdqf.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gt2ivtvjhjk.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gt2chvhefox.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gt2lbhnfyfe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gt2dbfsgtlc.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2oxakjhiz.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2ldhyxzuh.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2dborafbh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2uzxhwnqi.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gt2jngyoycj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gt2hqjzzrfi.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gt2ryffyeou.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxdpvdch.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2uinuqoys.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gt2jalluodu.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gt2gjzdbayx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2ityhdhhw.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2mavqfzno.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gt2zgmyshhr.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2tvueaorv.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhuohpnh.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gt2avsirxoc.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2iuoqqgik.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gt2zbadqdrx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gt2xykdqogw.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2snwfkpmq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2qhwhrseb.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2drfuzgau.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2gpcojjwg.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2mdljlyte.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2bwnfbeck.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2rdvgfprs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2owggvqoy.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2senomenj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gt2jqlkroby.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2yvlkfmin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2bspcoudw.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2obnvhgsm.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gt2vxhhlyjm.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpxipzev.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2hnajhadz.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2iavjyzvu.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gt2bxhzhslt.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2gmaurbpy.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gt2bzqxxqcd.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2wwvfgzyb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2kageifwc.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2pxhodxpo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kodabzzm.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gt2fjpjcgwh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gt2nzefbxko.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2wbjkokys.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoerfsfz.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlbgmwxm.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2gfpsyrjq.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2xnijwznb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2intbopyb.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2ltouwfws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gt2qhtlgxyy.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gt2zpfqcmwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gt2vnczjnbf.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gt2yoiywcpc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gt2ohjhifae.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyykcgiw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2fgohbzeo.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gt2qtcclpdh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gt2yihvsknu.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2xcqmyixj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2viydnwqb.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gt2sttakxuz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2asljbvav.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2eruplkmy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gt2zrfknzny.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2buyxpvhn.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aqsaxgwm.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2emdsflcs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzdkaofg.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2wvjlhaev.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2iaqeqlor.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2afyeobpi.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gt2qpsviioz.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyakuadb.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2olquhvjc.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2wvkonfhv.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2pjwvjiyp.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2druldxgu.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gt2fsgldsnj.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gt2hpfpdqhv.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gt2fqplwdxr.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gt2mvzvozwv.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2ourebuak.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gt2vavflmkd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gt2ajfuvqcr.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gt2ceeglehz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2fsvbtosd.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gt2eoulucmq.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2cetxvfkf.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gt2qostmfuy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gt2eladulli.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2sicaizmf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2jjhlozxx.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2cbtpfpwh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2xarfndic.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gt2ddizwesu.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdfavjtw.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umiergrf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gt2iqhtibnq.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2ulbleufp.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2forbsdba.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gt2kucykxrl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gt2bbjbofum.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2tmqdbjbm.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gt2xaqodvqh.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gt2mdojhtfs.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gt2kpzdgqqp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iimvjphs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2sykblvmx.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gt2vfojjcaa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyqrzufk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2gtsvaski.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2tyojdrqh.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2ieykjpux.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2kdzdczuy.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2iihwdukq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpnirwm.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gt2hkbzrlif.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obrdfzta.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2yefsnmki.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igqosiit.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gt2nwcqdsyd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gt2ttoqlwwo.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gt2kxbodhbl.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiijkhqb.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gt2ljfegbeg.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2pmtvsuue.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptnkeqon.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2fclcbcvq.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gt2khlqiied.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2wpufahvp.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2luhocxpg.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuvklgwv.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2mhwwlema.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2oozufntk.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gt2sjfofzqu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2pcnkutfp.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gt2reinsktg.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2akahtlfo.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gt2oasbortd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gt2mlcekxew.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyubhyes.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2mmmwvjvu.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gt2kvwlyclb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2jxeuxswr.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gt2lfllvdpr.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gt2bqdmqufd.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xucnpkgx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2vpltelcu.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gt2lselfyed.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gt2caoramik.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2obkiuthi.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2dxqwnbzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odlwzvdz.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmcbqcdl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2hewycdeh.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2mnqxdzlm.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdtbhnfo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hbbewmck.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gt2lxdqakqi.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gt2zdxcvjor.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2kvwzpofc.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2jyqrcjbx.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gt2fcqknbav.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gt2eyprjvky.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gt2ywayyfez.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2lypegraj.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2fegoabpt.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2gtoacebr.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gt2vqereamq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2xxknyqwz.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2tdhnhmwv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2txzhlnej.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvlrknrt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gt2nqwqnnni.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gt2hveuzpph.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovhbakju.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2cxjljnze.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gt2zukeuzqq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2vxhmsklh.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2syibbuuf.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzqxabxz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2xuprggso.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twvrzozd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2nvhdvqrg.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gt2rxndyyjg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2rritihix.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2bujipmuq.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2xkahwdmn.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2gpwzshoj.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2aarjzamu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfdblbu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysbfjdrb.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gt2eraebshs.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2cdbzfkye.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2hunmmedp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2zjmjgydn.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gt2dbrttftd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2ogskahzp.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gt2ixwavxxh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gt2gmcuozwl.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2cgawhvvo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2tppfvayg.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2demtsjrp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gt2jptbtezp.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gt2vxzinfgt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2dhpsluch.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbnfeznn.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tndsqdpw.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gt2arowhocz.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gt2fcieyprb.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2hfzplwin.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2juigqivv.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2jyditxfl.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2hrpajnep.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uadueupp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kphoejec.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2yaeqiyaf.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gt2vrximekb.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gt2zlcirxbm.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgauemzi.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulchfevk.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gt2jtqvnkmu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gt2vllcwkuf.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gt2rsjydnsr.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gt2tlrmbmbp.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2mwmnimig.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gt2zrxdslco.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gt2cltiqnax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gt2ksxoyavg.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2alwnocic.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oncnfbss.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2azamvrcu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2krczmtqf.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2cbzvvfgs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gt2bxbpmsso.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gt2colxtlke.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2vmwwkwii.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2ejquogdm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2cxjeiygg.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gt2nbihsqfw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gt2gfbsfvnt.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2uhrazgcs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gt2ahpqdlir.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2romubtbh.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmkzgcul.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gt2usscdkpp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvdnyovb.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiwfkgbs.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2imzikwww.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2zvezjqwf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gt2dxqicghi.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gt2dddksxka.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2kcbseyoh.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2uxfuzlfv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gt2ekywyuzm.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2mgbcddik.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gt2znryqdfn.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwjvoayc.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gt2jfxmeypz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gt2oncdovde.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gt2dxzzbpbo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzznyrdf.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gt2nyctugoy.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2stdgzlvj.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2kioqrzmr.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2khuzjjbw.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enlddddq.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gt2yngpitwh.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gt2rapjbqng.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2frnoxizb.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpfskjld.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2rgrscevo.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvwobusf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2pnyqilhe.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gt2hejgqdyl.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gt2hbozzmaz.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2cirqeboh.html


<!-- 参考信息 -->