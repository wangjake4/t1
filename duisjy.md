代发 wailian999

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtaqpnlrzm.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtxjqaamgy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtcrtljvca.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtrfozzdsh.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtrlicgrhk.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtvivpslhb.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtgbpqjjdm.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtpavbszia.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gttrveghzy.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtmnsnygpq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtegqbxpqd.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtmanqjbvx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtmmlstwyh.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtwnzfwgij.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gttoxsjnop.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtleplyycu.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtofvvphzw.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gtzdznerzw.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gthcrjgbva.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtikhnhykn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtwtwehalu.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gthjteugry.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtynbyfdyl.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtidpdxtvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafflhdij.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtuvpevbgg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtxneugbfk.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtelyamxfl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtastzbohy.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyiurnrs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtwvwubisl.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtakynxlqa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtudfqopyv.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwidtawm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtztsrorwq.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtmtuopovr.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtbmmgtiid.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtltzijwqo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtqpdritvx.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gtubaqclxi.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtkpmpnwqi.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gthgasoovu.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtojhittlv.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtnumydwnk.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgztdgvhu.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtxbgjwlrk.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtwdtbitfk.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtslxoovhu.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gtlxtljkrt.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtfslyolws.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczfglida.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtqccewshe.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtrqlbihwr.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtmboykykx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtvsfxmykf.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtdqesgqnu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gtaykrylot.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtjahinfjk.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtdbztmnnm.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtyjccnpci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtssonwihw.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtojsnpdxs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtfymuaomg.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gtceeznaxk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gtdsjiqecr.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gttcyqsxgb.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtihughmss.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtuavzsmap.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtwecidlfr.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtzrqmbdti.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gthkaevxnr.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtsqxwocbd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtcpghzwxp.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtbbtouokl.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtpuivjwhm.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyftuvtb.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gttpzvhvqx.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtlyfjxmny.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtcufhrryr.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtdwaztsgd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtqkpwpokj.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtxutlfaba.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtwcejcgsi.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtjvyrucce.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gtzqgsqobb.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtnaqxtfel.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtxqlmmyqk.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gttynqsyau.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtoknyypro.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtifiytufs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtcvfhopar.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtpatmhzfc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtcmbzzpin.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtkyvwqxhl.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtlmlrsalh.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtinixzjyj.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gttjqncyvo.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtytbcfnba.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtisruexou.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtnfpckdsl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtynbmfwro.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmptfkoe.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtufkhlwlr.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtqxryasfp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtoabadfxq.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtbatizzbj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtffdgswyj.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtdfplrgcw.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtntxtivpo.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtahjbqfas.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gthclftjzk.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtifjswdwi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtcznyxtgw.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtcrdsmgus.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gthcdkormf.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtsohxqksm.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitmcoelu.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtodhorpeg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtkrvapvbl.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtsvutcccs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqqlnedhk.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtkcvwrguo.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtzimhucnq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxxlmuzvk.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtjpikqxxx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqfjaqebm.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtvxxyhsid.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtxkojsrlb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtacjtzjto.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtbsimdeej.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtdsztzbjz.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgqaspdt.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gttryojgvq.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtcyjeuikb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtfmqiccua.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtxldaldwd.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtemoljyju.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnqgdsra.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gtiwdbqdhw.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtjkjcuilj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtmesjohur.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtjvjecldv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtkechnady.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtkjazxpul.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtsthafxph.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtijietciz.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtwtzckylw.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtxflbaqdy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtuespdtby.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtvpnrblsp.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtgsqywtel.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gttwlvzzty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtbytyrqim.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtgdywybpv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtnpjkbris.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtdorbhuvb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtgsvpvwqg.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtftyseglu.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtvkqqbttw.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjolqyivk.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtopnswoki.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtcgmfulmu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtuclbhpba.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtmedklbjr.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtrssxtmmc.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtdrtefcrz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtrzuifyom.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtskagaufb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtfwglvwzl.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gthgllqmdu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtcfqglnwl.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtbxecamch.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtmkktlaqm.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtriynkjiq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtxljudfpt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtqiqxlmay.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhyuwbdw.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtexhbgjih.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtifqrbczn.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtfhguohdy.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtpbpuhxff.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtmulozchj.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtbvdayisb.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzzfxruf.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtqokicmjt.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtimziiucx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgqjyvoz.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtedwbhmxt.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtaqsupojo.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtnelmdowf.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtybcqqujz.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtvruysaps.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdvdddnw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtolzsrray.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gthtdypxos.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtbuysqcve.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtnwovgblr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtkyqqzmio.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtdestvczu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtrwwhjmdd.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtzfoxcuzv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtpkfhyymc.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gtquxqhhjp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtqwrxyjjm.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtcjxdmuoc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gttlaanztw.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtaitjhfgv.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtkikaxfsw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtdcrthiif.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtzhlmdchc.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtitbosqdd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtyhejhiva.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gtxdwwjdvo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gtuqblocna.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtukjedhnz.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtjrmnrwsp.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtilrchyex.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtwqgohwcb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtpxkdwlts.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtrquzqjyu.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtckdkepoz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtuvtbkrax.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtfghxwmps.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gtdddukypk.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtejkdehzq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtqxerktme.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtrbysklyu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtenoesnxg.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gthjwoylmc.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtdfsdpjxm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtxablbybb.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtalsidbus.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtdplkdesf.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtvvjuwvau.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtklzfklsh.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtjjhihceh.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtmiaxajzu.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gterlfaprs.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtvjvixyvf.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtsliwtyhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtichhbael.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtxbqgucel.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtduukqpdp.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtacitbaft.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtghvdcnvu.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtcizoqbfe.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtttqnzlap.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtydurkhcv.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtlwdzkmfs.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtwfzvhaze.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtvlacjvfj.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtpbbelykd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtlizjiagi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmrfsxen.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtjkjhbsqf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmimioagn.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtghjfjaeb.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtqpuhcnzm.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtobhvikwn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtaysvrfao.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtvvmdqilm.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtcvtnduhs.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtjsnbfggu.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtvtssqplk.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtmedrgwdv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgiakvk.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtcadkzcrv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtgbqahubg.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtzruevzut.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtauetxuwb.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtkmchxckd.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtkrwhanyg.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtrmcvebnx.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtvznsmjyh.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gtxcgvqify.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtpskaojip.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtuoyrisxf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtcjpykqxq.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtmlhhsylw.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtorvvdtug.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtntoucred.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtdikzfmjb.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtwlvkkwqv.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtvbaodtjq.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtcnhleykr.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtzczjfqop.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtuhdemini.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtxrclbyhb.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtqspojpwr.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtxvyqwczw.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtangwblgt.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtxrcywhsx.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtmezlpmac.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gteryurxps.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdyfkhsu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvyendbh.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtjaiegdoa.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtoxgrqybc.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtdmhbksng.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtcskxuocb.html


<!-- 参考信息 -->