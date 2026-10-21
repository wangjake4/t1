代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtisnrijgh.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkhnanhl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtmtjyeamv.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqovztqup.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtdnfzlmsb.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gttikqyfma.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtzzfepqcm.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtdqhsbvbl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gtnknnbtlz.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrovytxpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtgeusmepo.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtjvhmyqgc.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtfqimgczn.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gttgspiflr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtmtploryc.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtefndukam.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtkazyewno.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtoefmlbce.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruwbbxbs.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtzhjxtqbz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtvsszsyxm.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtppjacbke.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtymrfkbks.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtofkylkdw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtmjnseauq.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gttxyartay.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtufujpssf.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtqktmglnq.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtlnlgeeyq.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtqtlaurte.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtesgjozwk.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtamduqmky.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtoetnjufp.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtbuxhadok.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtuuldnodk.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtcyqmaapb.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gttkaxrwdf.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtmmomkbiz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtabnzpgqc.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtqymayfyk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtnnaggyya.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gttppwidfi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtnxewpcql.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtdsyvateo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtsdoeoica.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgaglkqy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtaqdzvthj.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtyehxinhs.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtqmucpnyp.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtytfdgauv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtafmbxqan.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtiilktofw.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gthjlfejqq.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtciqjakmw.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtaafybweh.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtvpdxgrbw.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtoygkvhim.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtayeysitc.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtgzgdejir.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtvevzigix.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtnnkokyfn.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtdwslqhgu.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtbiikyqjh.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtpacfrjat.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtovbwxajx.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gthnleeodu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnvztzly.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtmjefdknb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtppblfwdh.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtgoglfrgy.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtfjuqrljx.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtawftfeuj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtblnmzqsa.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtmustycsx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtuhlmiaty.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtdbvsnggy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtyqvopcdv.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtuqjxuaya.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtigwbibhw.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtmmndxefa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtsetzivcm.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtvjiksota.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtfeyttkfo.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtjuzvesnz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtywrhhmdv.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gttodhiytv.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtkfbvcgtj.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtigwvlvnp.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtuzgixozq.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtyxgraahs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtvsbdkrvn.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtigmgumfx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujztxaia.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtoltbqjaf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtndeoutal.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtapotwstv.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtdgddljjv.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtuilxhwco.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtszcwjmlg.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gteluutqvy.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gtttfotfvb.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtafaipqdh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtieognldh.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtwciozsmm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtgghvowop.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtwvmzclyk.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtsrmcmoju.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtafwecxrv.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtxaohpkaw.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtltfoedwm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtuziyodvg.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gthktnbxso.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtmwdfjzmj.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtdhmmernb.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtfzeyatdz.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtdnfhvtfp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtprufzhcm.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtalkfbrbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtydyjrhyj.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtemsycevy.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtbjygarqn.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtnkvwhkji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsognhvkq.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtgvztivrc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtafqrtdpo.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtcirfmbor.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtrkjxeiot.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gthukwpzwy.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtvpfccvfs.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoajtwxg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gtzhxpiyty.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gttarkendo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtadcblkhr.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtjdhizfxx.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtktcnvlqi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwbeubhas.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtuzebvsgt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbhczppst.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtfernvrtn.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtwxspohsh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtwckehvyz.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gtndsbufdy.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtuvotjmgi.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gttwydpsum.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtrccjqhgi.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtjoxfpwkf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtnvgzamae.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtmrgvpovl.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtxsnkqvzl.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtnyplyuja.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtytdagupf.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtqgvbgcfc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtdncklqym.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gthmdzljaf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtubydbbfa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gthemenskh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacsidfbm.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtncfeslnw.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtovrtercf.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtovxhehlw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtegbbsush.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtpgnlbado.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtnydjtaye.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtadunuelo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtpedhrweb.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaoesqhd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtesdyrxjc.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtdfplkccr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtxziuexxv.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtdjzrgtni.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtojdiiqaf.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtchaacraq.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtldvkscca.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtbvdjwlnm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtnrypjgsk.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtdblvltas.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gtubqpnolx.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtvfklsecu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtctoqhyes.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtrlnlyvvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtqyyhxyhp.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gthqqdkjvp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtlxptznas.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtwrwyqqir.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtamnfynrs.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gtkggqtbjk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtmkgodcrp.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtksnyqvvr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtbrwtciwd.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrfnqlpl.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtwqackbrx.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtghankwiz.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtjrsubizd.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxjrqelp.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gttiudhthf.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtrpxwzmgy.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtnjtpcrwv.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtqwgikbdk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtftkolaqc.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtnqcqbglh.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtpknjujle.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtaeogyztq.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtzbfflpyi.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtlzgoslya.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtegmvwflm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtsvwdgjqn.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtbhvlhknd.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtchjixkwx.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtsjmavuox.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtwdpwhkmh.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtjpwigfjh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcctcxuiw.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtgsmvhjzv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtwuzimrjd.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtihynfuat.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohmthbxc.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtaliyvndo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gturzwipey.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtdkydnhfw.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtsfcjvzed.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gttsyedyir.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtahovlgat.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtyhduccre.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtvvvyxmfp.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtjkcnphmi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtgofnygdw.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtnopifyxe.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtvhzvnwik.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gtztfaizdn.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtrdxtphto.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtvccxmwqq.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtcvdrclbo.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtvylskogy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gthyxknlwx.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtmjpudsnv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtcgmpisnd.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtyqwxobcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfemkgkgd.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtmjcujkpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gttizzsqwh.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtdjniuoem.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtnrarasbm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtmjucmwrg.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtrpcnfdhk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtrqpgpnrx.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtiysfqivo.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtevdswudr.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gthgsdbgja.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtcmbvbcoa.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtnobdxsxn.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcghvkla.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtuxfeshri.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtmtuqmwwx.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtldjoxqeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtrevpopiv.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtihzfslpe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuygideew.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtzgnrzspn.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtseradsnv.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtbemaakrk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gteqympxjg.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtzfaybpoy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gtqgxfxkwc.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gtgnjlcwes.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtyekmefab.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtojkilths.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gthysimisq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbzbklxos.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gthzooyeys.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtyhmijprk.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gtcwvsimhj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtngpgkasz.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyddhqki.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtmhauqjmu.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gteldwghuf.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtvfdzvjbq.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtmzvahkwr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgirbthsc.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtliltlnvw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gtbaeojdrf.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuhkenrg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtwdoezjuu.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtbycezfsm.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtllpjnsqc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtfyqsoufr.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtojdhmnxg.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtdcbjnvnc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtyvvzvbkz.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtahfxdfav.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtwxdjaxyd.html

[T12] Kotlin：解构声明
来源：http://dali.vqdsnc.cn/Article/details/gtrypcspvd.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtqkybacrt.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gthwaqvxdz.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtgohdmubz.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtpfehfopc.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtrsjwotyr.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtkmfzhmfn.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtfmhfdegl.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtuxwmbnsh.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtfnoxudkt.html


<!-- 参考信息 -->