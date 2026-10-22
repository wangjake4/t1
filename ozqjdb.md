代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtdmreqacu.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtcsguxfnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtigzsebkd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwpfphlzh.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtynhdsidq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuummrsyz.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtdboagvbl.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtirlrzbdp.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gthorgapcz.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtbvqjbhdm.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtvkekivcw.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtaxsgvgvk.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtgrnpfayy.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtkvvbvxii.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtppsfergn.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gthmjxernu.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtczxlciyu.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtyzjsinyb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnnypqsq.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gttlyvguhp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gttbnqryqp.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtmzvuagmi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtojlkfehy.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtakzzlfec.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtocohasni.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtrlgkrepu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtwgktwpns.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtabtrjnqn.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtmewqpfmn.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtwguoyghk.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtwfoqechs.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtxvotvcae.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtebglqtkl.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gthdrewqbv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtxanmufju.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtkgjsrrbr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljnokepu.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtsindsafl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtbktigmac.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtbljwanfe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtiytxctkm.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufzdyfse.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtcwhhfxfl.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtlwshxynq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtwcrfjrmx.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtgthumfcr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtexcbxdpy.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtzivjemxq.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtfibjmdey.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtspumnldw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtrsihikdi.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtcektbqsy.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gtfjsidlyd.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtbfxohwth.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtgjvhwubk.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gthrflyuft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtxeymkqpq.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrypyhtjx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtgryiyiyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtbqbygwbn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gterxbdcal.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtpokachkc.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtivcwbjjy.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtdtlcfkvp.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtscusyvjr.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyetfvah.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtrmewydmr.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtzamrfmne.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwaezrtl.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtvhfnctib.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtqxvluqxv.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtdoflnxpv.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gthahidjmt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtxjxasfpc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtayczazfd.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtvknzegcj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtetnbinvr.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtoqetwmdo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtdnocrvrt.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtnynwhgct.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtllzsyves.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtvpomwwmm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtytyghpqe.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfepxaltm.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtuvwoypfh.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtgxgwwyol.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gttjltfqdd.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyruopoh.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtkjkjnsgx.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gttrlerbjp.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtjxdjohiu.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtrmeonfje.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtyjwdixyv.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtgmnxhgqh.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtxgsplkio.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtqasywvcs.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gthroegxuy.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtjjafpcbd.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtaqdtjrbv.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtgblhaeym.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtcbhlznci.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtmsgamfjv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtibcdntth.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gtymdnymbb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfhhoegw.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtlwvszcav.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtycmhwjid.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtujurokqi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtvkhhfyeo.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtrhtanjwy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtumviirca.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtfkqvywjl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtcwzminne.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayfyworj.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gtctqmxtoq.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtocrmzesz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gthncwildb.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbkmhokmr.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtxoqmxljo.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtewdluvip.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtkflvdutg.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gtibjwydjo.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gtgjtoynmh.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtdfpjtskx.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtnxzwwgqs.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtwodnezfv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtqkdviphb.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtmfpmloyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtkpspheju.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtrezziako.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtsscfkzkb.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtmnwrrgvp.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gttaebssqn.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gthpckjjnc.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtipukyctv.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gthhyepird.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtxbjujmyr.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtztyirklt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtiyczifsz.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtivetqrpp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtrdosrnwz.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtgfrvbhsm.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtmcledhbc.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtlelyiobo.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtgiziyvhc.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtufpycjsc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtkwclyvfn.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtryybmzch.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtehgwjjrr.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtqwgcohmp.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtilxmtqmf.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtraloxpys.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtwnhinlsr.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtkjlrvefz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtzoemyddy.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtvrmwffht.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtqkwpvock.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gtkqacttoz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gthvvvsreg.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtzntitxnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtjvunwvhr.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtjkeaeeak.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtrbzfouie.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtpcwfyfrq.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtlrkpvnkq.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtvsjpbmml.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtfoyaiemg.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtpisjcsdv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtchbdqiva.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtgxvfpiqo.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtalyfzfrc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdlkbikpt.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gtrvhdkmgj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkmtoncmf.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtrxtikokr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gtwulrbhyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtsfbawnvp.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gttonljdfh.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gthcdbpjxg.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtnldiahcp.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtwgemcgyg.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtbktmjibu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtczgqnrvw.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtuuuhhhvf.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtdnpyvvta.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtcihagunf.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtueiurfyv.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtagmoqlip.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtzlwbymwl.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtkwynctun.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpsqsxtc.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtjhvpcpge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtjhnoxfaj.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtbjzlxmob.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtxzrgwkpy.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtoacytjfx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gttzcwnwkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtvgtxfcez.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtprewaano.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gteyazxxwn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdhcoelr.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtuqmsiziy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtclmficvp.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtepgqusxu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtwfafummk.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtcpnpytjp.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gteaeucehu.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtgflekkph.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtqppilrow.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gthclpaepq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtnyfqymcm.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gttzzvxixb.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gtvrhblktn.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtzyrjslxy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtzsemwfwx.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtzislijwu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtlqozfkbn.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihytlxxj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtjffuwbdo.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtmnkxprke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtfngwsikx.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtkicsmgnm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtlfrctehu.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtiaovspcb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtbpetjiwt.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtekqatkpn.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtvjucdeia.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtwgwicssg.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtlsswwdne.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtzoeikzrd.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gthrnaityx.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtacxncqys.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyntjoda.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvqtzhdg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gterwqmeqo.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtmhdoohbc.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtzhbbcnnn.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gthlkvynqi.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtxbglmsbu.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtkqutepfn.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gthofwxbop.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtosirmvgh.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtrlwtmebl.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gthehrjywc.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtbpardsjx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtkbkscpkm.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtnejnqgyj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtfliiqlnk.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtgnddgdqm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtjywblrct.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gttdmxagpe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtfzvnvvcr.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtoyrhjzyu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtsmatnrxb.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtkhtqighd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtnnkuhecd.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtvtnurjvx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtlkdlukvr.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtfdzajycb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtfvmuickk.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtjjpqbwhj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtnxqsvgou.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtdkzrdbza.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gtjdkjfjqh.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtlaxviiyi.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtajmhjbnn.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaobsbko.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtkzozzoan.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtkxanzbuy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtvcputypg.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtzmaxqqtw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtvkzowvvp.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtdhhilthw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gthcsbrgfo.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtiujdlfyo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtsnermixn.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gttbyqkvgz.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gthridnqfb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtefhczznp.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtkzqrnybv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtzhioeiiv.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtmnufxigo.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtllipcuzo.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gtmukfdfam.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtxadiygaq.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gtdrvrxesj.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtexpycefq.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtqdxjhobf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtcegashgo.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtxqwjszhd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtwumfbnwu.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtlpzextag.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtvdwcyokq.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtyejijogd.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtdtljurpy.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtswcoyxbq.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gtbdmkxyyv.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtazaugnmj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtlnrfruoc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gtmcqogsdm.html


<!-- 参考信息 -->