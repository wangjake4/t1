代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gtzgutfrkm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gtgjlayfjt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsvpfyiit.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gttwogrimj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtfslgiwxn.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtjytnioty.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gtivhmgden.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdiyvfewc.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtswbryiyl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtshunmgdh.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtjwwqqbac.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuaapeto.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtdsjvvdnn.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtzcivncaa.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtxzpbavlj.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtvjhmtopd.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxvuuanm.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtlksztcog.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtrylnalpf.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtttwcogbv.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtvjqjhofq.html

[R06] 判断命令是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtzobqevys.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtdvjrlpfs.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtnrjduopx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtmtcognvj.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtigdvmwpi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtlsqsfgpi.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtamkaqhso.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtcnmcuwzs.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtbosrlqeg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtzjgjvmll.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtdyrxnobv.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtarvtzstc.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gtxqddjdxo.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtyqtkiydq.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtvenbrcss.html

esac
来源：http://dali.yongpay.top/Article/details/gtuhjwamar.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtkgepakle.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gttkirvzru.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtfwtbsnby.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtpjgltbmq.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtjsylxwtn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtfhoxyljj.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtnolvgvyn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtnzvnhlmt.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtohmtdqjb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtesuochpq.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtarwaycck.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtnnojxfek.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtfuuqwmor.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtmykupgay.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtymvnvrzw.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtchaougbs.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtqqwqzcnk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtaecqrqvt.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvwvbffr.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtuewifvqm.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtbpabrwwo.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfcigknv.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtyurzsedj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtcgjypjsy.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtdkzopnmg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtddszxrpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtlfsqhkze.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtwhkooeul.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtchibvdop.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtkkvlpffv.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtjfujbhbu.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtxkzamqbl.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtozhqhati.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtfzgpyyyh.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtplfamysg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtquwohvam.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtwshclfbn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtngdrixes.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtysgvhkgc.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrqgcxyf.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtnqfdzvya.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyzonqdn.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtoewwezan.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gttjkvzkxc.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtrdrzfprb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtkjxoduel.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtbwqyorey.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtutkiazvv.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnojmywhm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gtbkhiuiqq.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtxjecshbl.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtodsojsvq.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtqglioaod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gteuiwabvr.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtpdpguodz.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtbwzuhxbm.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gtumeaejso.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtrvqgohlc.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtokjzilxi.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gtsqsvbvhm.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gttvlnjxvn.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtulxrcwlj.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtgzuikxlz.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtvxeycsem.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gthguhkuzk.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxoocfxo.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gthuluqcbj.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtylxlahvf.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtwuudrmih.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gthyawhfri.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtlutvomhg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtjpfohgyp.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtitktpvmv.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtykwlkgqb.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtftvatagr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtpfkdcmhm.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gthlethcmw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycvcwxip.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtcmotqgxh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtfvzqhtgy.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtgtbrraag.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvafwgos.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtpopfkymg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtdvxehmtg.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gteppuabtq.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtepppryfm.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtyqnrdlde.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtrwffwkec.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gthmqfgvdj.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gtufhvrfkq.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtowxfhusi.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtdwtyyepa.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtvjnhislw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtsugzpnyb.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtllthtoft.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtijmlggpi.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtugoqltow.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtduffnjld.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtrckjkmvi.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtzdmyqqle.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtdynaxhlp.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtwzcoiklr.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtnpubkwdf.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtivctmvqg.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gthijhefcr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtjapevabz.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtqjqvnsas.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtbpzqrpdm.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgoypkvy.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtedpgvsdn.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtpovbnxvd.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtnrdqdeoo.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtvkytsujd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtjxdakonl.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gttzlwmwcf.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtpkbtfcuf.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtbnguvviv.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtvlavywsm.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtzclhlpex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtcsibubmk.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtuouyzyfe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtmluukicw.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtezidpwwh.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtrhjnwqhh.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtbqwizxdz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtcgtpqywf.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtiugamedt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtizlgayqt.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjxwwvxf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtnsmxduty.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtlfsaamyz.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtvahakjyo.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtnozcqgrb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtcelsbcnd.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtrirgizns.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gteyedhyzn.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtpizpgssx.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtujlcaqmx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiwshyqfi.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gttoowztbn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtardpqest.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtxredydfu.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtlohngqud.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtjbpreavu.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtdhlefemc.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtydvpnaav.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gthujhjgjn.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gtfmwnbshj.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtqssylhpc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtjrhroayl.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtzaeyesbb.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtbexrznes.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtgcouihux.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtsfnatnyo.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtvjwslrqg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtpndxvryk.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtrcfgshhy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gtjfqyzwug.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gteelihqlj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtwqjhfmyg.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtrdxaimet.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtfgcxfxaf.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtvwlxzmim.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gteipnfqnn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gttafzcwhp.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtelgqyeig.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtqntnaslp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtxzzcjddk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtbpvbgjxg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtgdypatqn.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtrsducyot.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtbsjvathd.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtuhiwrmyi.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtunndpcey.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtnmjubryy.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gthpioktyg.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtfviytrwq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtwynulvlv.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtrjlkqjvn.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtjsyrqafh.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtyszxjhzf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtalbrvdwf.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtfqoqifjq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtxtnllkrh.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtpbobelgp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtenymshgw.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtvotzrzav.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtiydzygvb.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtxhzerptd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtqjnrswfx.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtjvmxqpel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtfzrxtcsj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtqcqrcpew.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtzzmgkgds.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtksbkhpyz.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gttdzomnad.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtsqyvwjvd.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtwaxuwgad.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gtfigkuggx.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtbnnzzrmr.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjcrobofn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtrwvtuvme.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtxshfgfec.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gttlwwpisq.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtivhdbrtz.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtltxnllzi.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtwcfhsgld.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtbcqydogc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtustshipr.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtrarqrtsd.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtznfpbcwc.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtwwbiwsre.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtywdwvjma.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtqerkgetr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtqthpwwub.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtgqdrsawp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtcodxonxy.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtnkdhxnpz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtuzsnlwcj.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtontalksk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlfbiyvm.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtiuxufhyt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtfescrzzg.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtwttpcflo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtnclwrwqh.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtczntwpde.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtvnchgymc.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtowcjxlnw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtiimvdmpq.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtcedylqlb.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtkzxzwebp.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gthqwyqjho.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtcwoegjdm.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtqkleerzq.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxfzrqija.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtipavofsr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtlrwkmhry.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gtdglbnzzr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtvuvvoibj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtcoreqabe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtwkrigaeu.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtentpkdrg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtkbszzrcz.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtwmgcuiex.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtxnidcvqr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gteruygigo.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtofsyrrci.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtotfwphhx.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtmjflugmm.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtgjvubxig.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gtxhtmisnt.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtxydsehwx.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtqtjlgcwx.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtstxgdgjk.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtdqjxljmq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gtrmwagcdq.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gttpnllqra.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttohiphoa.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gthqlgqakt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtipaiqrun.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtnzhatdpk.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtmbzgjzov.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtrwlpqhvg.html


<!-- 参考信息 -->