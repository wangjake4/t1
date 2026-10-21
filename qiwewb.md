代发 wailian999

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtswcamddi.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtuotzfyhx.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtvllgyxkx.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gthjvregsl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtuxukkyom.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtoobzrmwc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtcfvzekbu.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoiytebd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtmevnespz.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gttlvjktmn.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtmjpzbigc.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtymgpmhpt.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtslvygwmb.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtmvkhzvvf.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtkygtokzy.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gthglyrqcy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtiuczedwq.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtqqyfbtaf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtvnxhkzsr.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtoeizwokp.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtthqmcowk.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtqwkjmvff.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyhdgjlb.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gttaxjdbew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtcswutgkf.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtqoaoqigt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtksqliuca.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtbcqwovaa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gttsgvppgy.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtjjzyncax.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtrywukwks.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtlthpxdsc.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtqzvuiqxf.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gtbwxegceu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtwdtlzgig.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtzdxkoppq.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gteevbcbgr.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlknhsij.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtilchqohz.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarljwlln.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtmbblmtte.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtiqoqdfls.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtmcxcrixt.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtrrepsqsi.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtdqdutbww.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtvzctzymr.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtqmwrioey.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtzjdnqunb.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtjevajjhk.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtcvbwmtrl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtowcodljc.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gtxcblirsf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtpglfggzp.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtganesahg.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtgliwmadk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtlsejnzcq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtbieaoaur.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtwuzvkbbu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtjckbutjd.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtpozrdvza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtodkoqsuf.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtmbsqjcud.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtrdtrsuvk.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtofhcpdvj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtkhyremzl.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtfccwibdq.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtxmcdtssc.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfrecngs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtepxnfttd.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtxfllzgye.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gthiqikjue.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtkgucwdmg.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtzjzthxdy.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtmfxicepu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtcsahjbcx.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gttqginqng.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtvvvceobl.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtksbizyki.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtngvtfcms.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtyfbcjqlj.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtomytcris.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtfepghjnh.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtucemwlfs.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwyspyjo.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gteowzkjxc.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtuhrldsjw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtnqgnkpdr.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtxycpneli.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtcseqbmmx.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtgbfexjff.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gthhgjrmcj.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtkgdmsgmt.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtwxxcypus.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtbgfytzfy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtlbtocbxu.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtycetzwcr.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gtfblfvtjx.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtltfwdfyy.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gtwcnfcqoy.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtccxocdpn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpvxscev.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gttmurfogs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gthswnsacv.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtnmujvtbm.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtyanljcuf.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtlbqqibut.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtqapwgqid.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtqauzidlt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtlaunutqh.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtlwktgoaw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtypbeuhbh.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtwhkpmdhu.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtmjrjasjc.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtiegertym.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtaiejpbyw.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gtipcmnkhc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtxvtxderk.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtcwdnbxfn.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtnrfrcmqh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnkqktawe.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gthectfuhs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqqugxwhx.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtencdadje.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtfbriqxlu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsferqyiq.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtxqbgalcc.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtcofizhls.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtuspjjijz.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtzcnuradx.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtawxomrvz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtxjrocpld.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtnifmmwgk.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtamfqwfof.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtayvygket.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtnjmcukfo.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtlnumqeis.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtcycjoxup.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtdnhyiblu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtfyrhhwci.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydmzqlgd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtsqaxdytu.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gterqwmcrz.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtmmtydovy.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtyxtpfgth.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdbazlaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtmrjicvjh.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtylcsdade.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gtypgypugm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtfwozusjs.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtmuvpchyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtbqurtnma.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gthikfceol.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtemkgfhlh.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtlrxxyaib.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzdzpibo.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtntxrxgnk.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtctsbmtsd.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtoqgmzpak.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtvqptgcaw.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtzbwkaukv.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtmptezrnq.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtoqbjmvdi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtlcvtumht.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gteqmwubwi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtaqfwbjol.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gttgylecxe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gttkgdxekq.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtrzrjgxlp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtplqomcjx.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtqaljrjqu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gthcazoaou.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtdllzguvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtqglwgylw.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtvizesoww.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtjrsvbyva.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtfpcszwkv.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtysyizhrg.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtnzzwmosb.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtmiovyuxz.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtchqpfngt.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtbxtpedfz.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtdlatzbma.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtjakcyuqf.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtbemniuzi.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtuonegjme.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtrmloekof.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtponloszr.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtsfbbwsup.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtkkegmzbj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtnefzytaq.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtydrpguab.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtydhwwfxz.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtruxerqlx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtjbqlowzk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtyvrmjfjr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtqxggqmsv.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtqvhykquh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtknnfpqwo.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkacxlgq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtzovpcfmb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtyckvclvf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtkqtvdlkj.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtelquwlrv.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtdjpsudjg.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtfvzcoqta.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtoycryvsa.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gteefwypgm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtjxenmbmb.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtmngdkgmo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gthociwjyj.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtozddysfu.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtownplbhc.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtvkvjgrst.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtxpsotxsr.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtsznmzdlt.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtbxwdbzuv.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtwtdwntae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtpzfbxvod.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtgvgguvmr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtpspmfbzv.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gthgzultqv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtjxobeazu.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpltiizo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtveayvaxm.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtaawyljkr.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gteuvkjbyj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtdpnjbkrf.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtnjmrpgad.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtqszfyhre.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtkgnoxnav.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtesvbiwjb.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtzttipnao.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtpqwjamsf.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtrqdfbllc.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtavbrfniu.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtekslebia.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtgcqfzshw.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtfzrzasgl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gtgttrvudg.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtupdoquao.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtoctibtaq.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtigqsumlg.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gthlesvvpu.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtbsekekkc.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqzzelkg.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtaofnclvv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gtlhwpgqnc.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtzfgsmdev.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtwnuvgipy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtosyizfww.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtqtxuljfc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxydfdxom.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtstdialbp.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtwnqtdvjo.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtytdyobfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gthghguyoj.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtcukrobzw.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtkfytjpgt.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtbnhxveqg.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gttcbdliwc.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtqdoekbaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtkqwawflr.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtjwlvuyex.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtoqkdgrna.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkbohihl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtjbpgafoo.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtsbdzugsr.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gtxmnliwyl.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtvqytaeim.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gttuwfavct.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtdlsubjiq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtocnckpkk.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtojqkvrbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtjxhjhfhh.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtejbvddcp.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gttxhcpugv.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtqdznpptd.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtdnkwsipn.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyywwlpt.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtqnjjbvcv.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtnzyzfuww.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtngrczttm.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtcnotysng.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtvnupwysr.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtgbzlsggi.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtdkmnqkct.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtzsmuplua.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtxauqdxlg.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtjmprneso.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtqgrdzigp.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtfiplbrny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtrspmvont.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gtmoiuegua.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtyxoyijul.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtyheifxmi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtzrgcusmp.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtwhyitzdc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtqpyqebnb.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtnwtflahz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtcnovqxxn.html


<!-- 参考信息 -->