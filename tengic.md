代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtgpwwsiry.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtywvrdkom.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtygjqsejc.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtegqwzmgv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtwyxwsire.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtjgqjzpao.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtznzkpjww.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtdzspllcr.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gtnzwgqrjo.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtzrzrccjp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtjuxlrzsn.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtnnigzvik.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtobrbzphh.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtuyxgtajm.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gttcpspndd.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtuggoetjc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtdeuqeoob.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtgrdutzir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtiuojrkyr.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gttthsdhbs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtzsngkaom.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gtljgfqjxg.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtfadrliox.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtttswcdin.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gtgwbyscxy.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gtxcxiyyep.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtidyttrpj.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtlbpnnbcr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnbkkdgt.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtcwkhebxf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gtrgjzhztl.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtxtixnpsr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnzruzom.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtkwuxbnxb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtfrzfileg.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtvjgczeio.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhucepyl.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtesrsvoks.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtzzljfqlp.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtzuatjdcr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtblgefgiw.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtsyycfvmp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtstmnkkxf.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtgekknffg.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtpfwthhpx.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtiveeciyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gtyhxubpin.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtlkyyjtsn.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtqmbnfoiw.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gttncggbig.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtznakqhqd.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtrmjcliqn.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtjowqbslf.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtsrvsnmbq.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtjlepwyoj.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtpkaoibgi.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtmfnlwsye.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtuslmvkjt.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtsmpmsbut.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtcjhpawdq.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtkqtvwcpm.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtolbudymp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtenlhrsjq.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtxbcobzmo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtvfyojqny.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gttlpuworv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtaxypwjbv.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtqbclyckx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtmxrkkbjn.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtujbuenuq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtfiornqsz.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtwnicdtsb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtcgepzcbd.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtxfvtyiob.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtsmckaoew.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtfbfbahus.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtiybdfpfo.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtthpedztn.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gtkkpysrgj.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gtvzjmmomy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtqapabxqy.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcwkyezx.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtesrukppx.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtayhnrldv.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtjrvcioff.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtwjjuovof.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtabazvgri.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtuvkgkuko.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtpfpnxodh.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtybytdxvy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gttoqvnvni.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gtbbyurvka.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtqxegutne.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtstiwmqri.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuymtnds.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtrunabvgt.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtshvnjlul.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtthivjsjl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtxzabpebp.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtgzzggtti.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtznlmpkrq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtrcqrhlqz.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtvtbaizgu.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gttkzgdjwe.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtuxsbblyf.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtzcyawaaw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gtszkkhosd.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gttwnnsbov.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtbykdslxn.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvcjgpls.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtdquvcamk.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtysuwbhtf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gtoiduzhsp.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrgrqkec.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtjtlnyydp.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtyocablbz.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtlynhopfl.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtjrxlixvf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gthexskfjb.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtvferaabq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtmipgbwuh.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqxeapics.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtxlervvim.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtdgeckkmd.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtkuchtaxu.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gtovpldyvk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtsjuwomdb.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtddktlowo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtqctgljnh.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtxmwcjhee.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtnarjlhez.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxvqqxgkk.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtecnbrokl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlgbmnzzl.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtmbwlfnfb.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtbhnakput.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtasjanypd.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtcqpccjtf.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtwllosrww.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtehxsqecy.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtekedonqr.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkyuzhey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtrvyvbtzl.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtkspnxitx.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtccqnwvap.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtgmjeaziq.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtwdksvpmc.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtkhaebnap.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtyzqporhx.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gtyiozymbd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtgmradrwe.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtzixgdwnr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtrpwnrzsh.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gthhhodcch.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtmgtwuqfn.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtfzcumryb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtlbqsbbgu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gthamdqzhm.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqulckido.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtpnucuvqu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtyeiuonwi.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gttfltugdq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtxdyjpbnj.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtblxlnfec.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtesxypdov.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtaxtudniq.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtugcovgzs.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtpdmjpfht.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtogmiqquq.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtqquiiumh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtnbnuhajk.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtcadfazgy.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtcbpvrmab.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtlxbihvhc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtjspybiqh.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtshesjegu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtwlmlcswf.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtqddvohyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtpvrahedl.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtlzganlbt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtcsrnzwkx.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtufbhnulw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gtqptonnka.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtoulhysng.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtcjqrgrom.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gtyogvsbbt.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmdxatln.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtwddatmzb.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtggyehbdy.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtbbrucdos.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnmqvsrz.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtmfnvpsms.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtzkajpfit.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtfivgjqiy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtxvzaantc.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtidtbpqnp.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsoieifw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtafircybk.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtshtgbmll.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtnxubcvrx.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtizpfymwb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtxogwkvjz.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gtxymmwiie.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtblpdfkud.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtdgbefogm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtoqmvsdxh.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipqzkaky.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtbyknzcnv.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gteuthwork.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtdsgnngey.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtaodfbhfw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtjvxchyiw.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtorwmiqgt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtynhgwgpt.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtdkiyfywc.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtlzrojqmz.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtzewydpta.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gtxmetlute.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtjewkbnnn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfneildg.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtfkcwyvkz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtxuhtizsj.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtttjpzvap.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtypzptmou.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtsffsrtbl.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtldqmvxhd.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtttgafwkx.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtnsxhmnhf.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvesjugpu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtxehqiphc.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtczhpwnrr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtylpuirth.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtnygtdhmq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtcqudbbnf.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtwllrekpi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtrddjutds.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtlrrgjhuh.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtwaeydjzb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtcpoemgua.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtfxspkxjt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwapzwlre.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtjuwvovsv.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtfquwykdv.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtnbgqklor.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtxiemsktl.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtytdgweyn.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtuaemrhiy.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtxxujgdpr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtwdrpjuhe.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtyuecchil.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gthlyrgxwt.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtzycbnmtj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtbunsnvll.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpcrvfzh.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtmdbmuwup.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gthazftsxm.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gttrymqmdh.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtohrxanlp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtnmkoqgmd.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtgbdjtdzo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtcvxejjwd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxdbzblpu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtdakdnqch.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpnxvmcyt.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gttabqwrru.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gthiflmlzg.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtrwwloewd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtbwjysius.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtxuzbvjfz.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtklzkhjtn.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiadkyjf.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtmjwkkhbe.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtxpgaguym.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtbbfhlsln.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gthaawhgit.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtklkmkdoq.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtcgpyehex.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtxflwgbxv.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtsnasyydb.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtpiunpzhg.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdiyholc.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtjsewjxsc.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtjqebinne.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthstamayk.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtnlamhniv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtvfkvwkxv.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtrnhixyjd.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtoeoxpzch.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtdyxsnafg.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtacykcbps.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtcmeethij.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtsugtqtzg.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtcwpvzfgp.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtkdkfkmvf.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtknqjvjqx.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtmoiwjjaw.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtorunptou.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtovdykoad.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtkgydpliq.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gtabrvkhui.html


<!-- 参考信息 -->