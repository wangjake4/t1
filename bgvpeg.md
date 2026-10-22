代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2glfndeal.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2tmmvedkm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gt2vugqjkai.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rlatyivh.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gt2kgawhsqk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2yysdicjn.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkeuiifg.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2uzajadib.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gt2rzokfjde.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhzqivry.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2csxbvevm.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhrwoeqw.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhtioupr.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqcciipu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpyhdytf.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gt2gmjcvalc.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2hqjubxer.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2sfgoffgg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2oiebxskr.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2tzlhpfop.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gt2bjyezome.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2afwkenco.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2mgqvothp.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2qdchsbfu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gt2yekbwuqb.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2apwbvoti.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2bnxymvtf.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gt2ojkmbaji.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gt2pivfbujs.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cimcsnhd.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2cvyynpcy.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gt2ukynviko.html

esac
来源：http://dali.yj202588.top/Article/details/gt2qifcthmz.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2otseeikg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gt2iwobvkao.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2qhvsfoha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2eiqnfijs.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gt2rirminii.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2fmzkkbjy.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ahymgnsz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkeikqhl.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2tgnbpkcq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2rpvtyngd.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gt2nnsjneqd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gt2pnmznobi.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gt2andifswk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2nknhkjzc.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2apvtpyvq.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2asvbzpff.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2birmlqzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tveomhcn.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2haydtxbq.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gt2rtccuvsr.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2qgeaoivx.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2apikyfyn.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2agxkvxwn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2mqdadbcb.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2quhqrxns.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gt2sycbfrbv.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2xbgflbxt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcdjbzit.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2xtdzpvxs.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2eckzeujd.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gt2yfucnqfq.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2gjcfbosp.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gt2stmmkmum.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gt2duoubvol.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2pmjhvwnk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2hujezaey.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gt2bgevtdkf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gt2nwpyuxdu.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2dmdhypyz.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gt2cntiakuc.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gt2gmsnccaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2txlkckul.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gt2tycqhenx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gt2adkddtdg.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gt2fhaanrsh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2fgvxxgev.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gt2enfwcmnr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2smivefcf.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2ozugxbgd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2hhjpgolz.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gt2lfnbkahe.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2quvcexco.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2lidtytmi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gt2dbjtfwlq.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gt2zciesahh.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2lgvvrtaf.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcomtllf.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjvvikux.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2nfmqbwzz.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2epmjpgpm.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogguokhw.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2qfqphwhu.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gt2clspznwb.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2eadvfcgd.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2eneyysrw.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2ncbeukne.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2izpwqbfv.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gt2xpktoxif.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gt2ytqkxixv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gt2jbprqjyd.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gt2vpqprqhp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2yttttuna.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gt2caqmoihw.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2dehdmade.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2awbbhvhw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2wmpqdcio.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gt2ouusdddl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2plfzlvbf.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2xlhvhktw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2neatjwyk.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gt2axebjoch.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ldypqdju.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpfyqbfq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2rvxlulqa.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gt2cwoiketz.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2hredielt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvxioaj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gt2pxsrsnaa.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2vajvcfmi.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gt2doqepdiq.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2fytowqrx.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulrcczsd.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sswovqsh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gt2cfkoppfq.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2dboqzovc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2jljoubtz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2shiydhvl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2agkbcbil.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gt2brlbultv.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2knxcbefi.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gt2bqrwwuvw.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gt2kauyyfse.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gt2iqpidrng.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2mofpifqz.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gt2anoajazf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gt2nmkmtmbp.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2ajsokowj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gt2djzxficb.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gt2ktavyvnr.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxqycowm.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gt2dprjpxzp.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2rsqzupls.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gt2dgqpcrzl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gt2wcyvfzdh.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gt2svoqhiio.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2bucocvzd.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gt2jalynnsu.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gt2kvnggnfl.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2khdvvbvi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdwpjmhd.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2ljhwevox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2zozncxfo.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2sltdxreo.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2emylwqbg.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2xkkluiku.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gt2wgleqtoj.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2txyfrumf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2zhwztdqx.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gt2bzckvogt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2puoqvaqi.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2lzcdtjpf.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2ulwgqopj.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gt2selfvpwu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdbijjqf.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2intbchib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gt2emuqspaj.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gt2czmkcunj.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhqtndzi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tserzchj.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gt2tdwzoegn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lnwzbplq.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2mtuhuhjy.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2xuohfytg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gt2ujciqaqv.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2jochwuuj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhabgstw.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gt2rzmyirpk.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gt2jlvharep.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gt2gdvvrdos.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2fvpetfxn.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2njryhtkm.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcxpzmgy.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmmcvudm.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gt2hfvjwfsy.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2lcartlzl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gt2vdmzvwuc.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2mlioijtx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2kabxpqxi.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2dlstsqfi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gt2ihvksscl.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlzaaabc.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gt2qgyeatev.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2rdjgyvca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2trevsleb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gt2insmvhvu.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2amrkppzg.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gt2gmxawngo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2wvhfbglr.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2ibhpehcl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gt2apoiwkhj.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2aezqnxdv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2whbzkfas.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2rbckyooc.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gt2kjvbmwav.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2viezxxgw.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2rglbukdl.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2qcmopvbn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gt2iqeypgfv.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2phskxlyr.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gt2wlqgoxsz.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gt2qbjeexij.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2ygxulfds.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gt2diorrunq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2ghgkjpdm.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gt2loyiwczr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gt2wtjpuzlv.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2ofguydka.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gt2jzegkqfz.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gt2yocbobdq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2hoflzyls.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gt2iuauerjx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gt2gxpmafiq.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuidebxu.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gt2rdrfdwld.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2toylocal.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxpodzbq.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnwlwibq.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2myblbvzv.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gt2yojtnvtn.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gt2derynduf.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gt2liyhvaul.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gt2sxqwjgqa.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gt2rpojivwj.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2hoqqnuei.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2orkxcywc.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2blmxhroi.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2mngklfve.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2ckktqeef.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gt2vinqhtiz.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2ssvuxice.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2wyasuxbp.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gt2jfteyifg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hixyvukb.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gt2jqztwwjv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2beycvkbr.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2jvddltmt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdqizcoo.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2zfrorbhw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2udevxjwl.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2zxeubskj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2qahjnkat.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2wngblbmg.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivqvlick.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naafuzgz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlaoesij.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gt2rsayaecy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxxoloqv.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gt2jqvoehkk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2frdqukac.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2zhvzvsel.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2aknwrlwb.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gt2ojgvkdop.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gt2hooupabd.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2fwsazdcn.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vidzjncf.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gt2hxngywqu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2ckqfdrgp.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhcgzjru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kilrkdii.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gt2ulvxokye.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sclggarq.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2urnqsjlr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gt2ckksitsl.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eitzbhtp.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2cfusovqa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gt2ddnvqkci.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2qjgzwxfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2uteemobd.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okghryva.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckspiknz.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gt2jsdkaymh.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2pmwiwedd.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2foaohncb.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2picgnsvn.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2xllgzudh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2gghwxlfg.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2gmrgkvdu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2tqlmmjss.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2kywggqaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gt2cygicgdp.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gt2qqenrdvy.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2yqvxdsmt.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqylhxle.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuylwidi.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yshrkfpl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gt2jwewbosb.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjgciemv.html


<!-- 参考信息 -->