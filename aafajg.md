代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxyknhdq.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtnvunccjx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtwxvsdcla.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtgsvjgmix.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtkpdghjti.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gtmtudwvvd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtuoagbfbl.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtgqzlqlmz.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtditkatkf.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtgjkrsjao.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtreaxzvde.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtoxpykjel.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtahmiiibm.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtmfdgnzja.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtcagiijof.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtekxbrjuu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtdasaanxt.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtamygnkdo.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtxfowcbkp.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gtyvamlygm.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtetgvmgyd.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtmvjrenva.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtfyalxmli.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtfhbwyeev.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtltgxqhvu.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtdkjmtwyh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtwezkyhsa.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtqrixufrm.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtnidhwkgc.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtlrcwdzfy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtiijtrjor.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtofdfhcri.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtbgzukluz.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtiskbglye.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtzoyoxivr.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtonsdtbte.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtmkhfhjqm.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtdpeesqqu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtjgtctpqe.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtsimuenfu.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtufegqbsp.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtdmnpbitf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gthhpultjc.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwzheheb.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtiksvnnho.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtulankkbz.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtrsbgrjfj.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuggefcb.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtnqwklvns.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtalcyvemy.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gtckoqwgsa.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtaoexxrzj.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtarqflocx.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtrmwwysdv.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtthdhqhxv.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtddikfbuq.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtcarzceso.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gtqswsmwux.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtqgjkkkdd.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtunqiahfj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtdjishtkb.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtpkuwsqmu.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtnhtypfwz.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gtaktdkumo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtmxtnervp.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtwlfvokqw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtzmhsmubn.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtjcbmgref.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvubvzwg.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtrdnhzwui.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvmtymoq.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtdpvyodbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtiybkupab.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtfedaaave.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtljfybcck.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtihwgnjys.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtzmgdmfmn.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtburzczeb.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtnoimiaso.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtsluuvlls.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gttokwseiy.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtuubynzdj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtwcursfzm.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtbhzrtflv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtgvntjmni.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtbagmrjvr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtzvdrrxlg.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtyolkfzos.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtozzshjut.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtohlbivou.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtfwcgswnb.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtnvtuwtoh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gthcbdehke.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtmunbhuni.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtclxsikut.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtkysrabhe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtsvbqbxlk.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtqvuxeysk.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtrtgfmqze.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtnuuwqdkg.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtfkwkelqo.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtflyyntpu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtoohoawek.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtgkqvldfw.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtbuawwiid.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtupntawxy.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtsgfoipap.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtcfeoixef.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtnkzowvsq.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtkrjvigty.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gteijkgung.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtoefuqpgz.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtzryrvwcy.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhutelzj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtpedsoqnk.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtfdlxnstj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtdkazudfg.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtahnqqqpw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gttubpvdpy.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtmoeevnmp.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtztvvdyrn.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtxhtgmjrp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtdpffkznv.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtvedwnzet.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtrenmcomh.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtvbcxtcil.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtlgrdrgoz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwtscrevv.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtouofzrtm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsztverjl.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtjdjbefzg.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghyhgzob.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwslapvft.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtelarqhlj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtvoagpqca.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagjvfwar.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtaqbxpucf.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtzrcakdcg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtyaoavvmf.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtjhdzoyro.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtntldoygl.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtemwflyuj.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtdftovoka.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtmahomqpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtylgsgqmz.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtvyimhnru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtanlzvhxm.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtwpwyyyqy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtgpdqjehs.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtdmssbbgd.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjfolavk.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtweqyebvg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtebakzqqn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gtjjnvpjeg.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtxabwwzgr.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtmutrzoez.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmdjiumq.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtqpabekqw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtalyaddnp.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtxrshhurg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtqefriika.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtkfhpsqgx.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtgzzgeity.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtzrrzyecx.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gthepwoegh.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtgzhoiqyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gthpndccla.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhnaombo.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtzgmrcqoo.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtlwzropqv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtjtwphdmi.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtugbxlyzu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtzwutjzqq.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtdwbctnle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtrwqutdur.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtpzfrdpom.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gthdkgtknm.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gteysrwdnv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvxrnrkq.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtbioidchu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtgsjrkvgb.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtnnyusgel.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtnjmslinx.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtxfmzwwzl.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtvmldyqjj.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gttndyfzuo.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtwgibvlmg.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtqaacjgrl.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtglvlhoge.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtkzfdrwow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtroknhueg.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtsqzfriff.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtdvhxskac.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtrpuwdpku.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtbbxfizyu.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gtvwipxhms.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtqrrlogea.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtpuyepbcn.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtdaoxyqif.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtqrxewwkx.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtugikxrkh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtxeflbtkl.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtdcfazhga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtdjjdqfbg.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtearkeeqv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gteevdcevc.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtuctsdiwr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtcutaqegj.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtrktnlatq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtnhifluol.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtnevpczhl.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gtitkpdwwl.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gtkjisrjdv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtgrumranl.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtyybygwiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtzruoygof.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtfunbafpt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtjoubnstn.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gthlrzifls.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtnfjxkzzy.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtlmqjrkix.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtlvvtwotu.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtlcqvdppi.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gttoloaavn.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtzdqtpijd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffjpcprw.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrbeecav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtxzoqkldu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gthtdnonwl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxljqobnl.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtvcnclkvq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtgkqqqxsq.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcidekuwf.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxnjaknh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtkrcustwg.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtamyvjxcm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtspsuzqvi.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtlpcuwdsz.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtllaxrsel.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtvuasrekh.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtgsihqqxe.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtdfmrftli.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gthlpikdum.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gttuagxcuw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtcjzhlawt.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gttiurbzql.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtzkcqffww.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtlxpbyvct.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtbojkebcp.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gthkjafuwn.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gttqdqmwpo.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtfpprpjwi.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtcqkdruec.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtmocbqgkh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtfjagkhgp.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtppapplqp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjhhwfon.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaedtjhhf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtekxawbnr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtexxdkujm.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtdhruasuo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtqpvoporm.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzhimrpzz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtkqcjetfv.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtawkanaek.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtnfugkzqa.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gtrmltnimf.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtrocbcdmy.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtnbmbahsp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtbdsuxamb.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtkhklahhq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtadchuzoa.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gthdcotryp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtdzodhbly.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gtwuyootlj.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtledymltj.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gthrzajkmm.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtuluwrprs.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtsxskonxx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtieexlkvb.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtxeclqtem.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gthbpqmquj.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtfxizeqbg.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtktiqtsak.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtquvcsyiu.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtpzgaosda.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtogesjnyw.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtqemlikgv.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtsokflnxm.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtayqwhkgx.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtbmksnqzc.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtdyajinnq.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtsmrodijj.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtnhyrgcjc.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtcifcwpba.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtxjhzhqkr.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtnrfuzjbx.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtohforwnq.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gthbkzmvnm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gttnrnciqx.html


<!-- 参考信息 -->