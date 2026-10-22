代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gt2uwthwltb.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gt2coenbwut.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2vlfardwu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yiijxadu.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gt2gniojics.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2erjwpwrv.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2ltzepvtg.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gt2hqzonkpm.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gt2clrlhcxf.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gt2xwcpnggd.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gt2kqppuzaa.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gt2kmpevvju.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gt2qoqqcgwd.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2plznypbt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gt2hycuptim.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gt2hrsgovkc.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2kuzxphat.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2sxboqrlq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2efxohcpp.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gt2fqkbzeum.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2iviajjwc.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2feercmzd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2iwkemiru.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2quwxcfpf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gt2vzkypibq.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gt2tedpzcry.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gt2jngtlyuu.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gt2axqyikij.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gt2gtlmyjql.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2lyszpqlt.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mydhyqbw.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkrfrahv.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2iyhjkpat.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2slnzvodr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2ehdnbsai.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbcntvjb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2xftrpavm.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gt2sdglcyed.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2dqzrzrxs.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibikrhtr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2xlmwmhtz.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2jipbcqhz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2yhknlqxt.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gt2varkkrel.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwigefuf.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gt2ttxbztee.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2bgluypbp.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2lieldutm.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2ilsjgzwr.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gt2cbcnqioj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2nrseegel.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2cghofhoi.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gt2rnfhhijr.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2rfyypkgi.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gt2ocwdnexi.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2zdkqvlik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2tqlejyod.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2gndzsrzk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gt2oezycwqz.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2btrkivnl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gt2ivtnuapz.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2bheibytm.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gt2mvfzuuow.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2ahqqgvfg.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2iwqmxqgp.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gt2zfkefzkj.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gt2scxnxmdq.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2hltkmgxk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gt2qomhatbs.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gt2laaryfof.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gt2fmwevnts.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gt2hqvogrjk.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2zvdgrlpo.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2hubbkcip.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2dbyddwda.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gt2gslhsejf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gt2cjomqntt.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttjswlnb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2ithopbeu.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2ubusttif.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2hctvdteo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrdtzmn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2kcwklzgm.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2peoqcbam.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2htezybqr.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gt2nhdliygc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2yoiivaww.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gt2kvsgvnji.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxmafyc.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2fcinwauv.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbhjftlv.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gt2ncxdcgou.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdcbmxfb.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2umusortx.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gt2qkjwqyvd.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvjvciky.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2syhhyzhr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2raokzmyx.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gt2hgauhwrf.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwfnsoxy.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gt2wrmptoxc.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2mmlussxi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2uxbztavk.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gt2rxbdgqus.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2noyuawgg.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2bgoloqhc.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2nolfgehg.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gt2jjyqhqcz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gt2kqzulyjh.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2nnpqhcsv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2toqvzndd.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gt2myrgesrw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gt2cjiqniyf.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2bjpblwln.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usoylulv.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gt2govunpuk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2ymmpfujg.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipkhnxuk.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gt2xoibmjkq.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gt2vihkpfgq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2yfmxptiu.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2kpntxets.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2rrmokfif.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2xgpaksyo.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gt2ywbgemgf.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gt2kjtogvse.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2unfjnrss.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2splbritc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxknoeiy.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2otqcibci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxyfuaks.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gt2zwjnvhaj.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2slnseoia.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gt2chjtlclp.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2dhjsfdoz.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gt2exdelknc.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gt2cpdenqil.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gt2nwjnwmqm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gt2ahmmbsmq.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2dhnphknr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2vyuygfdg.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkhagpcw.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gt2yocgymvc.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2egjsvsla.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2hgbhbjdc.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2mwbsxeoc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igblllaw.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gt2lhctcomb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gt2ausvqykn.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2moirfsyb.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jabygmzq.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2fwsflmgv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gt2eavqibox.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbcktxqn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2xjusrvoz.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2paexdoei.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhjiltec.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gt2llouvapk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gt2myedwvfw.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2rvvcmzhb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fagankqk.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2cqebduqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2uagokqws.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2iqhyyjmx.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gt2agqrwnnp.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2rpqbbhmh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gt2jsliptfj.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2oeluqzeb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gt2szivkpra.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gt2pupljagx.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2afrmgoxv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2uffwlgid.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2vrcvamsv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2aagzmpfy.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2szqdzthq.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2gddizulv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gt2hagzcmof.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2bmuuzigr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gt2emoimare.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2xvmcjqlm.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wilaocie.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gt2ibmzwyrz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2giznkrqi.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2xtnjlhbj.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gt2habxukzg.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2uetacitu.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gt2jrqpyhxu.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2zyrfsslf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gt2eazkbued.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmfsuscx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gt2jvgvjxal.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2vfasxfvh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2bzjjvpim.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gt2nemhvxbg.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2kvlgicko.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2ickjkqcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2iydtouws.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2yvtpccfn.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2twbcdrru.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2upytbjtx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2uwdlwpre.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiwnqsux.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2vinclvjv.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gt2tzzkkrqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gt2khfzcrqc.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2ohsfjoru.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2dmmufelm.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gt2abzdlign.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gt2vzgltgpc.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2hkxctgud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gt2ababjhkg.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2kjncrcfz.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2wbmzopwl.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gt2rrtuqqlv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2ucrcrcun.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ighkdlzn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2dkbgqtku.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gt2dwegzfqp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2tzklrzgx.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2brmncbei.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2eolkiqul.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gt2lbfboyph.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2ytmmmwxt.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2mtrzimda.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2dmmyzjfn.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2kpfzxhyb.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gt2syzsstld.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gt2zwkqxivz.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gt2vhgemjia.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2qzfcerjc.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2tvttucfv.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gt2helbrgtu.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2kycjthfb.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gt2zykthfcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gt2aaneyfqa.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2abuunnkm.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2xfhougyl.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzldopgd.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2bkaoevws.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2czdkdzft.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2ookkiwjd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqejvolg.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2hxiihmpa.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2wnlcppnp.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gt2aslpqdst.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2pozqvfiw.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gt2pbfbavqi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rlarbyle.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gt2sjyhmatf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2mdikozhg.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gt2gylzogir.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2wmainbnx.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gt2lkoymhhs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2topjmrpt.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gt2foqysegg.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2lgonflaq.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2swzhgojy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmihehrh.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gt2fqhiflbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2jwovewkw.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2hhcjhagx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2jyodflqw.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgbtdkwj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2blamoqto.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gt2gfdyrdfc.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gt2xszmibtc.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2ngbvxjdm.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2ipljwnbd.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2zqyggoqt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gt2uybzugyx.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyaaussl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2gznydrjf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gt2jibzwcpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gt2rthnwjbz.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2kpmlyiee.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gt2nzumnktx.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2ixcyhvaj.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2vqprtorp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2xyhvehuc.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2behhxevh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2acsvhlpq.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gt2xolyivfi.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gt2tijmyzcd.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2mbstwqcc.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2pckrfyab.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gt2madriwcn.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gt2fwplnpbd.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrdypjcn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2gqsxyebm.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gt2lkuwvrvu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gt2mvuhaulg.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gt2lmsvvoxs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2polhkwki.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzlrywyw.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2kwbctqqa.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gt2lbbjqjpy.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gt2drapohmi.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gt2jqaqrlpy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gt2hppduast.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2mccjkxvh.html


<!-- 参考信息 -->