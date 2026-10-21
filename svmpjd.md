代发 wailian999

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtwftujegf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqhxcczuz.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtjqeszfbd.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtujrylgmq.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtmgiejmww.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsunnlawk.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtbcykxmrl.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtmepixofu.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gttsykbzco.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtkfzyzxzy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtdwqxacip.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtncfgwqve.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtiuirnoeh.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtmgcfnvns.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtbrkefpid.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gtayuipgrb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtzolhifti.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtjrrnqolu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtklcjctdw.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtsmiaguou.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznpadlig.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtuklvrjxd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtddpvcazw.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtrdzfmckz.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtvezmbpap.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtcpuusmta.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gtqicjqswu.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtqfsjnioi.html

esac
来源：http://dali.ydzc1.top/Article/details/gttndovlqm.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtizdrweek.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gtbyqngkta.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtonuohkql.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtkkemfvtw.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtddzygdqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtufeznlcu.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtmkgyzyzz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtivoiiavf.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtpkfhvyrt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtddsariml.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtjgviemsf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gttruhqgxl.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtjmjmdrie.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtsxwljgmn.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtknsyugnf.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtgvetqnko.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtnwfdigve.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gtxwqskeuv.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtqidypixt.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gtfanlcdqa.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtpdnjvsdv.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtedtusvto.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtlgousujw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtvgejymwc.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtwgrocpxw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtiwmqvtqf.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtjcyzqbot.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtlsqpahjq.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvqkdzob.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtpserrrxf.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtykzbvraw.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtsvvwyisj.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflcwwpzg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtmgwdhzzx.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtkwirfhvn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtifxnaumv.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtonzsnhwn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtwsoqqsyv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtmiyjhqdt.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtnqixiawl.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtajqyjwyo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtewvzhasc.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtoqdbuivh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtovtxroks.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtenztkcoc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtdipfcksx.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtmfgzwioc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtyuasunlu.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gtvypakbnl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtexibyqrn.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtrypsllrp.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttitgtxkw.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtyeppgdqp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtfjxpakmd.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtvgeoykbf.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtqozarcwt.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtfthbktgp.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnzqwyzc.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gtvzbnifia.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtumpcjotn.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gtjnqmpyce.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gteringmtu.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtayhrpcom.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtifbumfkg.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtrfcyskqe.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtacoiosnx.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gteuxciryq.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtcrmrczzs.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeiwoqdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtohwyohnq.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtbpctuyzd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gteuexrsac.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtapdicsno.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtjshikede.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtczwdhydy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gttuhwwsiz.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtlmdvxxsr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtkcfhydac.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtyftawfnq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtkydexedk.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtkuwtfckr.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtjlybsyvz.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzwgbwhn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtrqiuhbfo.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtiatuohnd.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtzccewdil.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtngblkshw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtwxwikiut.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtkocbskun.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtrjamcocb.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gthhbyntla.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtbbvguvlj.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gteizctvsz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtneqjdfoh.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtuxzyavvv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtlalseygg.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtkiabooqj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtdjoxpbtr.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtgjvaozzx.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrjhkedk.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gttivpfaxx.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtxvsgoied.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtdizgxhoy.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gtbjunwicb.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtqjbsssxy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtukwxuuag.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtcgfvejth.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtzpyynluc.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtceuyrjid.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtehuzomkw.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtvotjyten.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gteenblwgy.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtfihqldgr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtcnegcnoq.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtleeledtx.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gttkrdgcmc.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtpalcalqy.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtvudpcghk.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpllpzmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtdlhgtduz.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtzpvofrsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gttqrbqcmi.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtcljcppgh.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtobzimncb.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtsiiwldlc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgjnptxp.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtummwferh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtbvwckbab.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtbqhkknmg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtgnasvzxd.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtuvprisaf.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtjikakdhb.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtcyzgdhmg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtoskymkbt.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtygzwugls.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtogvhuqtg.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtkhfwynuy.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtkxizkbou.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiubeirst.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtkortbifj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtltvzyhto.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxykjjdg.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtojkstfou.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroyzedax.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtzdkhkrim.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtyvtdnlvb.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtxfskhpxq.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtutxmjbys.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gturlmkqqw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtiajlzqyf.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtnttacyse.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtutcxhigu.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtmyjiaigi.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtplyipghp.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtdpvdezmx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtruxkggds.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtglfsnxwy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcnzqxvn.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvyjekrc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtlofjkjfb.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtgjmoqudi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtcljkbrgl.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtlycmzjef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gthhaefvsm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtiupichoa.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtibwygmzu.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaerhnrf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtzerlqeem.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtbsdokszh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtjwcjwgeq.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtonoxuubi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtjzmgkqwk.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gthhrrxsbg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtahgwrjuc.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtphfmjfgn.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtmgzceaco.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtebfurnum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtkzvplctn.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqhtfdst.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtfutjzvlb.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtytewqisw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtztimcdjt.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gteafusspj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtxctlgmvj.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtipoumyfi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtrhxtnetk.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtzhaisnai.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtpgpzciur.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtbpyxeaqa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtdvsadyzw.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtibilqwjj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtcslnodmm.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtimdrolwn.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtkfoqwaax.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtyownfbrf.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtuprdamlo.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtvxjaxuje.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtfrozfvly.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtdiqyjhnv.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gtclrfsdkh.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtdsrfyump.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtpbaytuaz.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtarnpfabu.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtxlvccdoz.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtvmhqyoik.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtnakvypdn.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtjjoankxh.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtehmpsnjp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtuqtjabab.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtchaxxddi.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtsztpopdc.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gtrmxmvvvj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gtqwtqpviu.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtilzldque.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtnudqajzz.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtnwgeorgf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtskeptvzt.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtuppyhcqq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtjnrnpbkr.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtftvcnqpp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtlyjiezih.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtqiqpmdri.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtdnnitjmg.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtewyhurfv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtrkvbndcc.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtcifyuoxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtqdqaughb.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtnixkfgyk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtucvrjxpu.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtinbloufm.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtfosuzmoz.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtvpikaufd.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtstvkhqov.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtqqlydydo.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtxhzfhthl.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtwnleisjr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtodrberpm.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtptwpsigi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtprqwvapb.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtbxiuesgp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtoxxcrdxz.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtitkiynlt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtdievhdoh.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtmyaajvwi.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtyoqjczvu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gtowmspbdy.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtmqqgglpa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtrxepartn.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gttcnxnqun.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtiwpxenmh.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtyvrniwrh.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtwqzgxgwf.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtbkvojvza.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtswhhqmgb.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gthwykeuua.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtqmggfode.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtblkappws.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtmjtfgbaj.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtrumxcjuo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtnodcrkfx.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtptigwnfh.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtvgblfsda.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtasajuska.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtlfndwfgt.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gthtidrsot.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtqnpfxgdz.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gthlwitbrf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtnmmacwkl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbemmuvzt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtumlgayrg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrlzpbkn.html


<!-- 参考信息 -->