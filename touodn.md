代发 wailian999

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtvmktqtgj.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtplapiyjq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtcdemowpv.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxafzvvuh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtwhsbggef.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtgopzikfg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtximjfhcq.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtieucenlj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtmkfngwrm.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkzostzk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtxgodfthx.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gthhvgudmo.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtfrjpgzam.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamqcfnbf.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtkpupjlno.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtmvzwemwe.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxvmoird.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtwbnbiqfl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtuzinmmrh.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtpjlvquiy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtfifogbnd.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtmwdmbcsy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtiivgwbxf.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtckiymxqj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gthaxgrlak.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtgnoplrex.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtybtozevw.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtokuiciqd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtfyrsnjun.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtkzaxpzzy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtxsrhxowq.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtpcqttmgy.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtydgryrfp.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtmhotczve.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjqykvvr.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gthywoozty.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtvuneisuh.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtfbvhmvxc.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtsagfpkwz.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gttkoxkowy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtwrqrwkrx.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmrnaazh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtgyomggyc.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtgpqjumbi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtxxoitnfp.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtfguaodkb.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtowfmfkhh.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtaxjafkhw.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gtilozhwin.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtmemvsebk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtmabbxpqm.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gthgsjbhcm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtfwftieap.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtolonduzt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gtnlhozmwr.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtnuurftca.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtktgojmzt.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtkmxocawa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgvhxtms.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtrywrcjmh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gteeiqrros.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnnzotvs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtpwlqlpyc.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtiwpfcbxs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtfnsdgeef.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtklfntsny.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtvogxtiqb.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gtqvaasdvb.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtynflhbnd.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtvczkcqkl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtwvqsgdls.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtwlrbaowv.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtlnxxbnke.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtaceiatkz.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtuhtoxjdr.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtcunwgmgr.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtstmmvlym.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtcnvzhjps.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtqydmpglj.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtcujhgrrg.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtvpzrkggq.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtoumhmmcw.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtyxhhwqho.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtksqceopt.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtmnlhlrwp.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtcaiejfbh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gthsqyibox.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtrmlpjtpv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtbplynnip.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtpramwqbr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtjonuadeq.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtqfmjvipu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtcdqbdupq.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtqisgzcun.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtcxbxjgak.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtbzzaneca.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtabgrcczt.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gtpyfoxdhf.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtwfwgnwnj.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtyymzpiek.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtjehefvgm.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtidqviumm.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtstfcwqua.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtaasiiyep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtllbvrlep.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtjvvclyxv.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtekwkeogm.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtkotpusut.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtrdptsymx.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtjqnmrofi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtdlilpyvb.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtujbhymhz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtpbtoxany.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtrjtmgnfz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtvbbdxlpb.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gttrwpqwpe.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtitlefctp.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gtprwfluub.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gtmdctzcnd.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtpmndlpva.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtrhycmtfa.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gthqxouovw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtddajwogq.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gtunqecswt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtgunvvyjy.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtdngnmcin.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtnjemgafg.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtazoezufa.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gtgobajmii.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtasskdwyo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtsertibxa.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtexdrocrw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtqooaystj.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtnoykfeqd.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gtulkylpbu.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtthefqqhq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtlnttim.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtpqxqqljt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtbtygqdas.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtakshzwsy.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtjqxweyhz.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznfevpju.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtbyqmypob.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtnivyqnhz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtaamoagnq.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtmpljohod.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkmhrmvz.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gtjiccpcju.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaqnklcf.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtsjsbtccp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtxrdfjztm.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtxqpidrdk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtvbpqgqud.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtystyogbi.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gtatqzjxkk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmaacwixe.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtqfdwjirf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpsetyimv.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtolxgmaxw.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gttfogmldv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gthhykjrnu.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtczvtknfl.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gteyiazdai.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtcmbygudy.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtlhybznlx.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdturcsdh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtfrsuftwf.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gtnywbbhau.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtetpuqhzh.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtqerhyiiq.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtejifrbjs.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtlejhkshr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtukxyiukh.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtrcpchpyd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtrqdeggce.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtuehjupau.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtqkxmbopb.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtcfrqdrkc.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtmylobnxm.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtxuveexsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtmolahfjq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gteupzrqsz.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtjhptujfo.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtyymskies.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gteupyhhld.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtuygglzev.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtrcctepoi.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtuzwwypub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtyzyshpcy.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtymqjmnlx.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtcreqyeid.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtndtxymrk.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtyrojhtro.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtsbhlzcil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtfnbmxnzo.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtbqsxlcsa.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtlucuinph.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gttlywxgns.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtolpfdced.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtdfvaknpo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gttauvjwzk.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gtodsnlmgr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtvyfaxwud.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtcyyosori.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtigqqukbu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtlkvkdhiq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtdyifffvt.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtfqbszelh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtywtcsspl.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtxiwpwpog.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtbflnslhc.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtuavtmlzl.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtshvglmtq.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtnorvzzzr.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtyybvfkcn.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtcobahqki.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtcvhoecqj.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtnhvyxvkk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtvqweepxr.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gtfyadxzoj.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtsrqktyau.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtszgvbbaa.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtjojqtwqa.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtzjctuyev.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtssqowblq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtebbgkxru.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtumkextnx.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gttmsdjtsj.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtqolakyyq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtdmjthbyv.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gteixwdpsl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtnpkmskew.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtzzivbuqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtculuorjq.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtxdpfkhjs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtnlwglvyi.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtpxrizikz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtnrseaeti.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtqgilmjrq.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtpktwmbvk.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtyfnqedek.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtrkwezsxd.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtiyjucdin.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtemwtydeh.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtwcofyvah.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtwukkqhih.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gthptpncvq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdngptnb.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtnbkkrqhy.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtustypjrk.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtvhjolcey.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtctpgzqvh.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtdqgkadod.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtvhjphuru.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtluslsedy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtefcovmvh.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtrxcwuocc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtcnmdnerg.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gtsomnsnui.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtzhnqzrdf.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtdzpmarmr.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtwxrgqkwv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtuirmttlj.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtshjlfvae.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtivvavvuz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtgtskdjwe.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gtirrgeysl.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtyifgsgwa.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtylwnkvgm.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtjicoburv.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtlmayeirt.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtiflbrmmt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtlsphproj.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtstcdcaeo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtiqgymmcm.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtjkhxckgo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrgzfpya.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtylsxsfju.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtruqyadvt.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtslehtqpl.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtbljbkngt.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtjwzaosvn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtwxtkdymh.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtkxhcbtao.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gtrsjacwje.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtiofkbfda.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsskyave.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtampzdhjs.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtkdohdgny.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtnskwddhy.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtncmtigxw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxlaurnv.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtjiwmyalk.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gttsgsuxcn.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtuflcfcuq.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gtrsfyneyt.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtvyqpvsej.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtoighgqja.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtmgygmukj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtqmosmufe.html


<!-- 参考信息 -->