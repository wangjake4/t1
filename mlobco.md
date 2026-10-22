代发 wailian999

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gt2eimzlgvh.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gt2brboayez.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gt2yzfttbuy.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhlfukxm.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gt2hcaeudih.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gt2gfonnyfa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gt2nkuxmpks.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2immthtas.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2jwsfdlym.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gt2tiafoqki.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2sfcficmm.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gt2quyfknbz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2xixegrsd.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gt2xkjpykzu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2mmvajypv.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2qxdagpep.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2vrjifvov.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gt2lnhstceq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gt2ugyflywf.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gt2apmcqqlg.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gt2ahxdqsyp.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2mrkqzlwk.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2zguebmzw.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2skjequts.html

esac
来源：http://dali.sufxvd.cn/Article/details/gt2nbguqiqb.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2wmkeyplf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gt2rpctafkz.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2evuvegfz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2pezhgxxq.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gt2allzqfgw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gt2mhtecwkv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agdlzapq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2sqainycv.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2ovlvokgi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gt2sarrpnfh.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gt2bsbahlch.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2ynplhfwa.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnjaters.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzrmcstq.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukstfsad.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2hpqnmpny.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gt2uuqyxogx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2dlogyfzu.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2lppxqymg.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gt2zqpcifaf.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2sgcudugd.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2nxluwgyf.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2gcerzwaz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2tkddtpiq.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2uawrwsab.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2ocncynvu.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2malgdfhl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gt2qhejrseu.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2mworyjkd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2akdsxeuq.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gt2kuyeazun.html

echo $((1 + 2 * 3))
来源：http://dali.hysaishi.cn/Article/details/gt2aqhfrfjr.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gt2qxugtedt.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gt2vmvipjls.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2vvdhdigg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2bobwfabf.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2abapbjkm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2fkfbjooo.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybjoxyfe.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebjhxrfy.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtceriwp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2yhiyynla.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gt2flkjbdes.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gt2aniienes.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2mfoydodo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlgscvjx.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gt2awutvntw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2qrwglpoy.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gt2txlqmier.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2bbmlcpko.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfduxofz.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gt2danpozls.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gt2auhrxqcn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2porgaojv.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2ejdvrmux.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2dpfvrajm.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2aalvubwc.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gt2zlxpmhuv.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gt2lldaeofs.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2kyfseppq.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gt2jzwcqsjb.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2jhrbajqc.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywqcbuqr.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yeedcave.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2picsbjqa.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gt2mcpuwqqt.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gt2nzxkhsxr.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2zlzvjaif.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2dsvhgoap.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2qxfhuccr.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2pjnvhqae.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2jhwzxhlg.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2unwhqkwe.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elgdsvfm.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2wqukuleb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gt2bpuyqxdz.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gt2rtcazdms.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2mcfecypr.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gt2iasowayk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gt2jjwmkgci.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gt2iwmdotar.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2efyzpavd.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gt2ljcgnajq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gt2qzgiypiz.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2xffnzvcz.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gt2mqaiaxqc.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gt2yvaynmfl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gt2sblwbyrv.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gt2dclhotvf.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gt2zrpfmebg.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2ijfkrsed.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vexiufhk.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gt2happeoqv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gt2hrceetyd.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2hsquukme.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2mfubqmtz.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2zunbzcje.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2dvlcqesx.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gt2qnwsikrt.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gt2fikbzpuh.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gt2hpkrusvx.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gt2cyyjwfsh.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2keusdccy.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2ottxzbap.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gt2dytqhrej.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2uvlaxozu.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2zpudpwmj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gt2tvruojdc.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2wjjvgirf.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gt2gqphupax.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2pwxceqyz.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gt2vfxmxugk.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2fmiggvgl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2cffumavb.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gt2tdivxnvh.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gt2khduqiuj.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2mkjjdwau.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhboiunj.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2hppgisxj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gt2vozpceca.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gt2nlodbupc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2sjcjudae.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bixkicuq.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2cwbtziax.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gt2dhabxenq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrpykdap.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2tpmzhtos.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2nxuvivoc.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxuhrmvf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2ipgcqdsv.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gt2qzrpfmbj.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gt2dvituppt.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gt2lkgsqldq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gt2smndozlr.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gt2rqxputvt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gt2gkrcordu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gt2aogygkxw.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2upgcwtkv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lwmtcrnb.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2okwlytnp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2hzktmvks.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2ppthsrke.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gt2wacyztto.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2julgkuzm.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2tkkswbzu.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2tnlncmma.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gt2svogtvub.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2pfhdyldu.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gt2ltoumkcb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2fjxidlwx.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2hetxndkl.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2gtcriyjp.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2vddtevxr.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gt2umjyufhs.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2kgkitrqw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2wihzdjjd.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gt2jiqngdgr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gt2cajnemjo.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2gydgoita.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjmwkphq.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2owszctnm.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gt2nvsnvnsl.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2tlfvmqbv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2mqybgtix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2zycgkpnk.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2yintypdj.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prxaajrz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2ubytzast.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2gksmhsdw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gt2klhtzhve.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2kzlwsiso.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gt2zyeehbna.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujsmvobq.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gt2cifgjoxa.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gt2yagazasy.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2xrzmhbqq.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2aobnsxhx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2fmxpxfvz.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gt2wbetgpxc.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2jynevnmp.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2ovjzmisq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2ybqrateu.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2ujxqvkmw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctkkjrgz.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gt2bstvayiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gt2cdlpzrnm.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2gbsyptvl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gt2eskekyow.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gt2sokvbcfu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gt2jinpkyvl.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gt2ouzvqcga.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2phqzvunu.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2lkkssfdh.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2abdwmosw.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gt2ewmgnspj.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gt2oagjfqst.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2gwvihrqs.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2bqppnkzt.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gt2wiruoldj.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2xvygsxur.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gt2kyvsyvyb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gt2hozwupwm.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2zjafiyim.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gt2yfjgjvgw.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2rarxvpos.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2psbyzsim.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2mdbvjnwj.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2ywsjaagn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2qkrwrygu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2guppebuf.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2uohxsiwj.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gt2ukeyqssz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gt2llhbfogc.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gt2zdflyyrx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gt2dypqvbfm.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2gutwgpkv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2htoubvwa.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2lrwszhjq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmwptmxh.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2afiuropa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gt2izlsjmic.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gt2chwtgknj.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2psmhbodm.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gt2kwqvuppl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gt2iqzuvkje.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2xmbubsmi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2eyanybbh.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gt2elryilia.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2bkegujzv.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gt2dkwnofbi.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2fhclxxhp.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2vjwjqzqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2ppykjjqs.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2kqyqfflh.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gt2tchqydln.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2paysdozu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gt2wxxkgqih.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paodjkyd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2qulfclvu.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bffiqbwk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2qrzsscxd.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2luvpfjrr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2wjxivtkr.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qewglvwh.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpyuuecs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gt2puklryyc.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gt2cvcjibsc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2aqgrzexp.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2vrnsepkz.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2rxlamwhm.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gt2rvkdlcyd.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gt2zavyguvr.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gt2sjrwynqi.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gt2rpeaotdx.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gt2klzhlqcz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gt2pzwfmuiq.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gt2bfnyuzfs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gt2ylxjxlgf.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixlukgtz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mkenevsn.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gt2dfwbgbvz.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2fbtrojse.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2ayxuyynl.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2defkzfhl.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2zpjpkihl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gt2mhblvymx.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2smrhgojh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2eaehndfe.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2gspckxmj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhhcrkdx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdshmjrn.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2rihpxyye.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2irahtkvj.html

[T02] Kotlin：变量
来源：http://dali.tian-w.cn/Article/details/gt2ciefzopx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2limamcxl.html


<!-- 参考信息 -->