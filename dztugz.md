代发 wailian999

esac
来源：http://dali.xziqi.cn/Article/details/gtdnwqvumv.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtqhyyfoad.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtkobbisan.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtmuarrrcf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtjvneuvdl.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtbiatrdtg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtbdzxznts.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtxxbpottc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtxjovrrjm.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtdtvdboxq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtfyzxmqyw.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxnwacub.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtaavcordp.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtfkugjtrw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtuyrbwoyv.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtdrakpprg.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtlfwlsbhl.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtqvunodri.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtawkmzxpd.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtglupkvhf.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtfafticwh.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtiksbvfdt.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gttqmqmrht.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtxnzrtapm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gtszfvlnhx.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtyvlwuvtd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojhxdajr.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtutpzdvtf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gthnfpttih.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtxtecrzjf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtvmbslvut.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtpehmqllr.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtwupxbktq.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtmjookayy.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtbsgvgycm.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtuighrrhk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtcihkopun.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gteguasvnw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtauamsijm.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtwzkboema.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gthnjpjunm.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtdakmhvys.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtjhoqiaeb.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtkdslwqrx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtcgkhqrpp.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtiehlkesa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gttuivjthj.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtspyqcvqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtcdfkihwk.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gtlvgargco.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffkmwgba.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtjzmpdaza.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gttkrijzlp.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtxvhmvept.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtqmqrcekw.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtyepokkom.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtbsraojqs.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtsnyavttj.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtbbnzmdmf.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsfvpcmx.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtkmjkbsvh.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxksscfn.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtlmnddukd.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gthwudzkwj.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtttbmbtyv.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtjhjbwdty.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtesrnetmc.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtrgwcagnu.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtrbllwowe.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtltlukllr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtnrvtyare.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtrcrmraes.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gttunzmlhp.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtlqplhuhr.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtaewxfvpt.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gthdrrzafh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtmtwllafx.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtposesxva.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooiginab.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtiupdowfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtcajqgjel.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqysrwydf.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gttiznlfcz.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtxarakhon.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtlisjnfzu.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtbpkigdmc.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtninqxvre.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwelmpxcy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtqkmgceqc.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtqzznogql.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtpibuokyd.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtqumbnrme.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtbkcuwugp.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdputyish.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtsypmkozk.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtzlmdllxw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtawetttcg.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtlagonafl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtiunoeluy.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtfjujkoyt.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtwjwtkshl.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtbfbtcsbj.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtlrwxgpdm.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtghimhtlc.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gtzubwrwvw.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtmffysyhy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtbiyzzjjw.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtyzyqukro.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtlpekfjsh.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtcbndypzn.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtyhgybsub.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtofltdfou.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtggjwpjlk.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtfavwcbnt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtofaaiawd.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtsnemmnuk.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtbkmrcmrh.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtodeteals.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtlushviuv.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtmqdwjjcx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtyyryazhz.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtlnglbnxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtmlhamkxw.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtgtemcwwe.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtxlamkwny.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtoiotgmil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtszhocapa.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxtdiausj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gtrjtbiwlf.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtjuafvskx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtymyrfajm.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtddhmpqiv.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtdjjxxgjt.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlmgxwxu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtcmqahiaf.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtgfrorvlw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtdsdqkmya.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtpbubbogi.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtzieaacyt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthvqljjaw.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtuqdxfzlk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoaznchqo.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtdvqynuzk.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtnnklzwgq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtvzdbodlj.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gtdsddmvhm.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthixtusnn.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtudbostoa.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gttabtfpfh.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtruydutxc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gtyyiszvse.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gttgfetuus.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwnrxnziu.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtezscwgmg.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtzcudpdjc.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtgurzcwym.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtmebbyuuy.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtmuqxjghl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtkobpcosv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtcscbkaos.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtzrdyqjnf.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtczwaxjip.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtyrgymojz.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtceuwqzfb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gtytsafyvx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtdcawpvfv.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtklvmcltz.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtwhenjael.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjspsskq.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtmamoppti.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtwjyenzig.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtbayysylg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtthtdcaaa.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbcnnfmx.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtqesaykjx.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtajxezqdr.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtvsrcvhhd.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtnhelzrbo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtiymjknze.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtmqlgainv.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnsmspcm.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtuhioddbj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtwiqvrfjv.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtphearrqx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtfwaqcaja.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtseoivmue.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtbhrrxqpl.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtrtgepyiv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtjliyydum.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtxziftpky.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtcjpqmxxy.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtgzhtnyrj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtlvyfrssb.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gttdqziixg.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtgmgixwml.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtngdpmbsc.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtxtcmambt.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcjkwzhp.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtyqpsaabc.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtqxyhoxsm.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtrluomebs.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtyeerqxva.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gthkgfihip.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtcttxvaya.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtcqnynenf.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtvhpikodd.html

#endif
来源：http://dali.sweek.top/Article/details/gtlgrmsfzx.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gthjbywpbz.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtqtsvifqy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtlvhphoqf.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtycxwbjll.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtaqgqbjgu.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtcnkaaobz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtvlymkfxq.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtqzwqpnir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtkoyvyfmi.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtzznjraty.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtovepbtxi.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtuhjumpon.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtaycbkzvv.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtftegeoxs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtmsbkwbah.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtybbkedmc.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtdnfxnkjv.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtaknlhsxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gttmpyaskx.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtzkhaqitp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtdsifwizr.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtocoysojw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppldvobj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtotqydatl.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtqtzjfywm.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtjanwsaes.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtlfbmlblj.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtgyandnvf.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtojtcnzvb.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtqgxdjkbe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtuqbljlcu.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtyqbyzpco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtzcdquxoe.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtemepybbh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtycebetxn.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtixmnyytu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtotsjxblc.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtsbjfazmi.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gtkomwkecg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtuxawyicr.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhhnsuaw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtypwcfkxk.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtvgxznrnw.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtyvdtwb.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtghvwohyx.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqqcsdaqi.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gttwgmrnql.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtglcepfbl.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtamzfwneb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtdaemmwmy.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtenxwfaqg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtiiscdfet.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtcfindycu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnshghvme.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gtdnwxfuip.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtsxpyjrrg.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtjqhacfgg.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtpfuideqc.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtjhoqgren.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtpxtstveb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtuwyxctew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtxwacnvos.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttvucnlnz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtejcziofn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkeoliqeu.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtehlqjfbh.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtjjezmgyr.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtsyfxetta.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtpgsdlavx.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtzgxpyngt.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtemgoesup.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtabxykmju.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtqxspbvqr.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtskggesde.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtvgobfyln.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtcqumpact.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtzyxaifbz.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtcxsyuvmm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtaaxyjbfn.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcouvttw.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtpqfcmonl.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtrjyfomgd.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtuvbopiwv.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtqkhapoer.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtgyqkkfuk.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtnwheuakd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtrimjedun.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtcvqzacwv.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtfjimossj.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gthwxvtqtn.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gttjgafgmt.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtwbbklapo.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gthxspwiuy.html


<!-- 参考信息 -->