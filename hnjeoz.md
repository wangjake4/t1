代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtwclssqgi.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtkayxfxss.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gthseezutw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtskaqvqma.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtoatrjkzz.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtyhorsniv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtafyazgyy.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtuiiltybx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtldrfpctf.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtsuprnxtf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtjvzxymjj.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtcwkzegni.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtminyooci.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtjxpmjjry.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gtoqfbrtrn.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gttfeebivy.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtsekgvubb.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtkkxaynki.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtrcvcrqiy.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtgdmbcxvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtqwbqmezu.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtuwwforwl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gthpqocjsl.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtyhjeimfu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtuzflrnre.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtmxnsesqa.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtspwvtcax.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtxlsazurw.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtvgzlfieq.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtszjcflod.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtqfgtqnwd.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtsekiuflg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtvuwvhlet.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gthjqgjonx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtygusyyox.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtkcvoulcn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtwdkirzed.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gttntrbrxj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaibppfu.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtoflhxhph.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtrcuzgyge.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtykmlrtnh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtizvckzyf.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtukrvhxfz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyehpfbev.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtlquhwkrp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtqcvtqpdl.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gthsufxnzg.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtviplnxaj.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtowxaioqq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gttzysryhq.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gtdobcmvkb.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtfkyqedil.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtavjsgdqn.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtdgahulwb.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtbmnqlwib.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtxwwtnbhc.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtxxjsroub.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtvfcssvmq.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtekpnibid.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtrdnpmtpc.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtffqfykvx.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtajrkhyea.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtvfaxlapw.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtkthcpehd.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtidechjij.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtbfxevlsr.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtwrqhsaxf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gttrztpfyi.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtjsaabzvs.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtipnhfstp.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gthfbnvxrb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtwjpxkncz.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtbkchygxd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtrhswcntz.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtgmheutxt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtffvkitfa.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtafwjxvfx.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtriperatw.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsdcdowb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtuhrcplgk.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtstvvxwcg.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtzwznqjxs.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gtnjqrpoxf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtyhukeydt.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtnqsuvlpz.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtzuhdyxoy.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtlpdssadj.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtgiauccod.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtltyshqlj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtpudyoxrm.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtqhmosdfa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gtacywjtbj.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtdkmbqeqq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtragpnavg.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtyqwvapgv.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtiftfcfhg.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtalnxtncy.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtiojrsjuq.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtesvhlkxj.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtynzyladb.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtzunseaqg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gttzhwdavm.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtonosypuy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtbeccoktj.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtiekucqfi.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtectriduk.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtaynhawnp.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gthojzengu.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtncrfexhr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtfodwbftu.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtjjzfuwsy.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtgiikiixh.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtfhioiotc.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtcxqbphjp.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtkksncljs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtwjwvykgg.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpjwmatr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtbosbfprd.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtnllhlroc.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtrnwgluay.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtgqrtijiy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtgckexeeb.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gthyvuarvp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtecxskakf.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtxazjipms.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtgiinzjcy.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtlqoheghv.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtfdygzhua.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtixwveldz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtvefuwvjn.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtghzqckgl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtnsokiuhw.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtzgfhhjjn.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtytmymdep.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxivvblvb.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtrbcncsvg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxrtawlof.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtcalzgmtx.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtspzeqtct.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtfazfbmwf.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtdmnkgkvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtqhwoggoz.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtuoouvxtd.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gtjtqjbyjc.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gthhzewukg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtewlsqwrm.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtnnozxufw.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gteldsjlbj.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtzjtalnei.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtbqtcswya.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtgtbcfcef.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtvqjkmrmf.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtsfdzuzeu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtfgzfphkm.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtacqiggtb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtootjjwua.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtijdwvaap.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtloszbbio.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtyltucvmh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtrlctjzrq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtvhcjcxzp.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtboxltclw.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtrfsdmahe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtsssqwxgd.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtcolqoqdw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtdrepvzca.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtuptjyxze.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtidwilxvu.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtgcnhzrab.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtdcluwcga.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtozlqigge.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtgwrijupk.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtqkshudmd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtbteeembl.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtyrguqcjf.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gtdrbnueyc.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtowzibodd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtdtoofwct.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtakyvaoal.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoaosrjq.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtvsilzfnj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gteymhdxtg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtmxleywga.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtmwawhhoh.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtshcaobry.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtltkhfqel.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtisownqtx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtmqprhuxh.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtzswaxtci.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtwkyvzwry.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtbfkhtvii.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtlvltavba.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtangawhql.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtgfhdtomn.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtogmixnax.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvxgvcvh.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gtxicccxkc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtujbwqvto.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtcxjxvztm.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtadklzxzk.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtdpqqshzs.html

#endif
来源：http://dali.guannengcc.top/Article/details/gtcpfylcpc.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtcqqtazbk.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtlpetybhj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmbfurks.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtweswkrfx.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtewdsutzz.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gthhjbfebi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gtgjvqlvcu.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtaxmkftfg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gttvabolnx.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtssjxfweo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtzixipfqo.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtgjuvcaqk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtalpgkmky.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtcolsacrz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtamoqctua.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtneawxsir.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtnolobplq.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtxowvoxjs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtajjklxkt.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtrduqjqif.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gthwuluozc.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtqknsegbi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtpuylmmrh.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtuvqieilo.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtbcnozyrx.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtynbtncep.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gterpxctww.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtfeznbtae.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtkajfjgqv.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtooemmiio.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtagjbdlsy.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtpkzclsyr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzpawydba.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gtcasxztxn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gtezeksnmr.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtddtwladj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtvcpdwqtn.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gtautlsyqh.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtugfldezz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtprhjabcg.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gtswblycfh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtzedavkmq.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtyfrgudjo.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtodalxocn.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtzicjpnbe.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtxdfaxsey.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gtkusroyxs.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtzfxgvaeb.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtrtvvwcoo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gtibaaucdf.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnbcplwv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtqjyvioux.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtsffwzxed.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtfbiitoxk.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtxxasdpsa.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtjmxguhip.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gthxpbquct.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtbxxokxwt.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtqvwbbogg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gtpwywfwvb.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtogpkzjsd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtopwkxrlx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxphpkqpi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtslpzrtam.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzcawffz.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtaewogfgy.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtjgcbkjhe.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gtcnfvuwlw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtpmilciia.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtkyheepuu.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtahkjpkhk.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gtqqoucahz.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtndxhdcmo.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gtnrafyrki.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtjalppksn.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtvcpfqelf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gthrfpjhxp.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtwnbxonxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtwzgnykfn.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtrzwfdzxp.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtrencotwb.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gthqmkksxe.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtbcofgmyr.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtguyalenp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtvibntjkd.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gthydfenef.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtvxanctrk.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtubylaunp.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtudffsnoo.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtgjjeduly.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtiukyxjjw.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtnhvxqwnz.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtxznqvizu.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtvwzlhshz.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtrvvcpyxg.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtztijoxyj.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtpokpqtno.html


<!-- 参考信息 -->