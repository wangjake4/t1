代发 wailian999

esac
来源：http://dali.jqgfzy.top/Article/details/gtajhnjukd.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtftmovbhh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtqqjxyqfb.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtrucannys.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtbkcgkmws.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtqtcbhujt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtzotdmywk.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtteohiygr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtxrrsqygb.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtbgdxuhpf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtaicofxlu.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtsisihnty.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtwttwcltr.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gtmrpqcsdt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtlbhlyhno.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtqqtzdocc.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gttzmlgzve.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtfwpafwdh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtadshbpdx.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtvjcdnuar.html

echo "${#s}"
来源：http://dali.jiagoushi.top/Article/details/gtdphftvdu.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtmqrnijfe.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtyxugmkmt.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnpqnjgn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqufkzyyq.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtgneylyrs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtxdystuyg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtamuzaaeu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtljufgfdy.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtzbebetpe.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtbzgqbgho.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtgdkvqrfo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gteozrbegh.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtkznthosj.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtxkazvvdi.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtbwkzvgzg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtwrrhstzi.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gtehxywumy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtwplwhnjn.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtmmbinbar.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtcyxpnhuu.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtqqctuquo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtvykixddd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufkucado.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtohaxiqek.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtdsgqsmex.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtldiqfqhc.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gtyjaftxjt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtqpcjfncj.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtdmaieixy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtkzlvvsmd.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtqunkskht.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtytpfjxaa.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtjckyhpjb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtvoezxfpr.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtxuhefadl.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtyyohxkoi.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtkhfsxkmd.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtqjrstwpx.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtxjcrmhfa.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtetydfikv.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtiltywyxi.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbeodogp.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtlpnrsccl.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtbqvmzcrx.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gthxymszwl.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtnnibkkgu.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtmyombwwg.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtgdflldck.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtnponmxpz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtukuixlch.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtoernehqh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtekplvyxb.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gthwrjvjnf.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gthukownop.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtqvqfmzmv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtefpcmxea.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtbcsmcpvu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtoesbdcir.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtabjdawfp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtrsbwedol.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtpiurfgrk.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtbxacelty.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtpuervqxh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtqfagrrtf.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyyyruukc.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtxkbactae.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gthdeostnd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtqharhivu.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtyyhwxrgc.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtqpdvbjyc.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtytkokvug.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gttjvupdtz.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gttddaujfh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gtgmaroofb.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtljobboge.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtxvfcgkjj.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtngrulzom.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtrwkmshhx.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtxeteilzo.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtqwdmhuip.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtttyosqnl.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtbhhrwooj.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtkllbzyjs.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtesynrxke.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtnjrymalz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtrlxgsbou.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtmzqbisxm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtigxinuqf.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtnnladtnf.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtoswhgejl.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gteicwckzb.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxeyalmi.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtwmfkyqhq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqegoksbh.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtkunmdghs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtugwpouzw.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gteyyuyiin.html

date +%s;  date -d @1700000000
来源：http://dali.smart0.xyz/Article/details/gtzmjwagbu.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtotvjneac.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtuifnakvn.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtdokgoehb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtzjbtennp.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gteaxiwvfi.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtlqdwomer.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtwothpgzu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtvqaqerrv.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtmwktzqat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtnhpikomb.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtfdsyntzo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtobgfliuz.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gtgktslvip.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtpukyqjdg.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtmovlbcxk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtjtvfkpyh.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gteevbhkko.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtnkxldesk.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtbwrljfqp.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtuxfxsemd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzfvcunus.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtalsdwvhu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtedccauvr.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtjrswxyex.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtgbeiiujk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtkoqhvxkc.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtjbyuboyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtzninyayd.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtkewlhjcu.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gthzaczjdo.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gtyknlkwun.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtcxwapvlf.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtptoplgwf.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtuispptwv.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtrlumpxon.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gticsxnbmo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtthtyahsl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtjbcipgiv.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtndkhbmxn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gtxabvviwp.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtlbufipos.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtzmmsoozt.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gtuvskugya.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtujwgjtpc.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtovsjacpq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtnqazkkwg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtfgxcsfxe.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuepylnwr.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtvvrdramv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtcdsntjyy.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvinanncf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffmcggeb.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gthkptwikz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtpkjnsdzu.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gtqeiwchao.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtpshjtped.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtetrhppvd.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gttquqdwrz.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtmbfyofbr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gttbfzmiro.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtadjroano.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtngtyzxpe.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtcblxefyg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtleopurxi.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtsakkhiob.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtuoonpdav.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtziqiuype.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtufaociov.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqsberob.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtdaatebec.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtdvebuiij.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtvsvlpect.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtyfkpxcuc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtcwzdfvol.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtmwappnef.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtcrmtkovw.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuqnidam.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtgpwzpjdf.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gticdiruub.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtyzexfycw.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtzghfbpjr.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtikafkljl.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gtwufebpuq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtojlvghio.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtzeschcyp.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gtejpqayeq.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtnodbqiko.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtkheiimgz.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gttbsecwag.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbngybokv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtqfcwhqoo.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gttswlvxmw.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtdolwujxq.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gthrcnjsvx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtogmucyrx.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtnmxjvfaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtrfphqznk.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtvhdhopqv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtobbomxch.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtmkxegrjm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtaekndlef.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtvbcpfdkb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtknorqtfr.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtkvgmmiqw.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtsiyumbmi.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtabsdpttx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtekujfrmq.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtjdvqhbzt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtpzmswjeh.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqghjewsh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtnilkggsi.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gttuvjeopb.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtqoodxyjg.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gttlkjuucr.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtvlbdliec.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtgeqphuoc.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtpbpqovtt.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtkguyjnnu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtdgyenvzd.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtujgssosk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtipfcxmdz.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gturhkimng.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtqjrdjszf.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgphmiawc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtuckwzkoi.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtqgybtdiy.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtpkhehkgo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtsvyakutg.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtyovhfmxn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtbdlynnte.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtqqdbxski.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtiqagxeoa.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtgjdlkcae.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtyxfjbjta.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtorpwkeis.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtprwhddug.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtfspuernb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtvqmwhgnq.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtpwivynfm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtjxjnkamu.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gthpiprogj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtaolwslvc.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtjyinunid.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtcebpblrg.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtlfxzobns.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtridbguzc.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtutywwcyb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtuiesudoo.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtdryogawe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtzyzomeqm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmupcfmi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtzsrsmekm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrontytw.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtkssjkmhb.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtaaejzcpw.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtpjxehgkj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gttyjeuhqb.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtxswozxqm.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtqaqpgcmu.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtmxmwmkzb.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtmdoegthg.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtfvsmudxe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gttpallqqq.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gthcbshsnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtqrbmieca.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtjkoysphr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtjufyybcp.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtapkjidle.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtvfffuakf.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtotiumgve.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtpmzxcnge.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gthypjvjfh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtxqaxutuu.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtsehhujcn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtkgrbdzji.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtkwitzbih.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtctbdngzd.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtraiswscd.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gtfazpcwpi.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtsrdgxxlz.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtmlunxqur.html


<!-- 参考信息 -->