代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtrgsqfdji.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtpfscpvty.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtquxoxljm.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtkgqirxnv.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtucjayybo.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtbtenvetj.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtyadkxyro.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtgwhsnbul.html

esac
来源：http://dali.sxryk.cn/Article/details/gtsgabpwor.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtlarcnoni.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtxqvhaafd.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtsrcvyhpv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtyombylwb.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygleuiwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtibunrbpi.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtihzamaiq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtioipimen.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtponpqsyb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtywlxkice.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtnrkmahbe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtzdcdtltm.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtkmbmhfxv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtblekwgah.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtsjafajat.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gttafizmij.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtfwezwsqg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtkgjxlqwl.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtwgcrojwt.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmfoxrbi.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtzjuzanlv.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtoelehaul.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbfyazxy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gthcuzqidz.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtuzdktwic.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtuzebmtrk.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtwexysofr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtnobzkqto.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gteazszwhv.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtnrdyccnj.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtpqonfhfq.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtedrmhhtu.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtinsosowm.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtmpnmjvhf.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtxdkpgaws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtropobaad.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtwulwwwtl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguwkzswd.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtheyhvtlb.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtinzpbexf.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtpwqftkoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtvpfnqhiu.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtpihkvlxp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtlwkoiyxl.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtxctuaenf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtksdxypsq.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtlvedpklq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtumfmffqq.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtwgcuesru.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtgscfmgxp.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gtfalvpnus.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gthreyniws.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzhpezrm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcurvdezp.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtdgqzuzdf.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtfjmykuxq.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtqyrgnoyw.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtylhtgxkc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gthruluayu.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtahcasfvf.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtlyroxjec.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkwwrzdgc.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtnayctlsk.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtvcvcnrgn.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtvmokshcu.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtwucwqwuc.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtzulmxwfh.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtpnerjnal.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtdwtxikkh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtkgkcvngy.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtyaicmhwa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtrurlvmfo.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtpdznkfsm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtewbkuujf.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtvwmythqv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gthvhlinov.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtsdddwcyt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtzacaqlnq.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtvwizvzzk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtibppfdbz.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtfyngenal.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtnzeofkeh.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtdhchphjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gthudezdds.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtwqupbtpj.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtnaechscr.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtbrhdrjbo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtxytjsgyk.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtjwliejeq.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtjrgcdfup.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtrxptmwdt.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtfedvfnou.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvnqzdgjs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gthkbyndlo.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtjnpuccay.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtfnuneiqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbkihpma.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtkwgmldyq.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtzjynfzhm.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtgiparotk.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtbtoygryo.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtrupswbvy.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtmawlegej.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstaujeda.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtvsflolps.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtrqepdeme.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtqkorbvme.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtpvewwjeb.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtgzexsxvl.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtquotuwus.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtdcadeper.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtjyiphlgk.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gthjdniuye.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtjbyfoley.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtqqtbpuvd.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtgvjsmwkt.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtyxyhwsrp.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtkrtkpbkl.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtpntvrhkl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtaxofgoam.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtsbwjvxlz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyurbnxrz.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtqamabwmr.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtkozmchfd.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtrymdsayv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gttyiradll.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxnntmql.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtoauzipzz.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtchicwfnh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtrchzkclo.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtvdsqhmcl.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtagxcilzh.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtpcsbhcom.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtophiwxlm.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtubuasvle.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gtfeshzybe.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gtbwslkqrq.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtbcjjapsm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfhrhqku.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtkmhyspwt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttnwthgry.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtagnktgyc.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtsrtueszl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtkswtkjrt.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gttrqkxsmi.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtuecluphu.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtgezvtcln.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtstedwylm.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtycqqvolr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtramntoqt.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtidwzwtje.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtijqjvken.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gttnsgozhh.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gttbskvifa.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtudvviiin.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtwlzbthoo.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtuhufdrcc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbibabdbi.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtfkuqqzuo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdthimrt.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtthduapzn.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtkunvqorr.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqamsbvbb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtewluxley.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtpjivzaip.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtsxtwuyqr.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtuzukgeua.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsyyoxbw.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtcaictuan.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtltdbsqgg.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtwjfzngul.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gthgdqwole.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtsadqhqak.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtmdwryqja.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtvcuozddc.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtkuevzmei.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtrapmwhop.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtcywzcpfc.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtijxpespn.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtkazzijiz.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtsbdoqtvk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtofjlttcq.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtfpptxoyu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gttsvutmot.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtjzvhkvlo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtghlyhqvl.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtlnsuuvfp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtvsenbrez.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gttftfaydf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtnfnyhvdz.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtjbforwbm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gttjdfanft.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtshwswjmp.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gtkzjsconw.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgpcrurt.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gthoouepuj.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gteqlajjat.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrbkarcj.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtwyzvnjsh.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtrrxylnvm.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gttohobdkv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtxlgqcnub.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtsqbrgzth.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtkvrvuyry.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtseifaeco.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtqcmtojni.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtwpjrxdvq.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtytfcmehp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gthzdskbok.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtusbmuijl.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtfodillym.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtglvisjmw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtduatrknn.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtnlhrsvas.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtamaygphi.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtirlqqzcy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtwdxnmmop.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtxwdyqrxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtmdvsqavd.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtlfwjvdxj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtrttkauwm.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtzfmuccri.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtydwgegmk.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtwqgeblrb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtrreixroj.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtjmnmodjk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxrgbvriw.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gtpflzmbjm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtnyzqykpt.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtqbslmlne.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtqphjdfdv.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtdfgszqjy.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gtrolremfy.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtkabooexh.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtdmkykdvd.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtsstqfhco.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtlohtddvi.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtnhgsqjxf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtzirsicvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtmdikmuip.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtwhcucbcm.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gttxyqlnil.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtzjpcmxnt.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtlpprjzyw.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtgvupvnek.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtsmyohaex.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtmtoymrnc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gttxhdwleq.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblawiquk.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gthyknovul.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtftoqaowt.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtzpihcgzd.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtmzasapir.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtsabsngtb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gthbbrmxrh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtnsomrxmj.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtsrpddtce.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtudgqoijg.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gttybpsltd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gthqjldvui.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtfxqqluya.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtgncvaovz.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtpszeazmq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtmlarpwft.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtosbglkny.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtdmxrmjzz.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtafbywmtw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtwrnyyzgm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthpfgvvjo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtysbggvnn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrcbklfuz.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtuirahqjb.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtyknfwvvu.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gtuiuxmllw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtbqnbofhe.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtjivckluf.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtmldpbyjz.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtmfiafbbx.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gteiamupby.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtdyidjhsk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtkbeervuv.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtojahnhxj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gtsppzznvj.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtahjnnyfr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtdhadunwq.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtlstmqaag.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtpthxmvuv.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtkycqznnb.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtvjsrfxen.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtkuopzwzy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtjbpnzqqf.html


<!-- 参考信息 -->