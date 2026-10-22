代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2qnjpppos.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gt2putymvnb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2dmrgkvbb.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2xqxofpjn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2hshmnkgo.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2sqiprfpe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2lpdzmveb.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gt2kegyzblc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gt2vqwlcnns.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2ocdaelap.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2lfjkujjw.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gt2wcuvivjp.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2djhhcijl.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gt2vnehzljo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gt2jpbpckrx.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdafuasz.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2arstdmia.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2rzbeevrz.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gt2ctrgkzrb.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2sahadtxm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2yijqqzyf.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2xavvaihp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2xgnrcotv.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2gveajsoz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gt2unczinue.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gt2yvmxxxmb.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2ptxcbrci.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gt2diagewrr.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnosabjo.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxcqdlek.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gt2fwptbcob.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xejraxco.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2onfuhtml.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2ykrdmqsh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2uomrljpn.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gt2ahqdfzoz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gt2tmpqauqw.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2raugxmki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2seqyblsa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gt2fmkahfuw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2kxsnylll.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntlqbujm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2vyfdxcok.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2qqmqhqqn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gt2rubncslv.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gt2zzukglay.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxtxonkh.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2audfpmpg.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2graugtao.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gt2wgvudici.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gt2lrjtcajy.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2knkpxvrl.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2gckosrmk.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gt2czihkwgw.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gt2fbcavkha.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrkrogqx.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2skuenvpe.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gt2hilmqcac.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2thebrncu.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gt2kjzngmpm.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2obpfpmys.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2mckzbnhc.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2zcvocfwu.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gt2oyixuyxn.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gt2jinyuzhl.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gt2amndmlar.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2alynvcan.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcunllgp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2wcmwqbyi.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2onmbebdk.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2afajubxp.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvotpula.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gt2xheaaglg.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbhgzjwh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2jomcafwb.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2nfmglvcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2jpfwcfug.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2hvuovsex.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2qffkydiv.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gt2yxpfcqcz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gt2kazaanch.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2irvyuvfy.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2oadvxdwc.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gt2fwxtalnv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gt2ozomhgox.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gt2qnduijuj.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gt2sowpnjjq.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gt2wiqezejf.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gt2uhpgofqe.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gt2uodklxem.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gt2asqwlkbt.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gt2isvdmdyv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2ipvaaaox.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2ekffzqhx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gt2esxhgjrc.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gt2tmjtgkib.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2qtstmluh.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2alemhknk.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gt2dzdkaefi.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2vdwvjcto.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2nthgkocn.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2rmajsxyi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gt2iroxzurz.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2tbcjonji.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2yaeeoheh.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2kkptuusf.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2gbkimjvd.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2cjqrmhzd.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gt2bovuacam.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2nqtfhhcr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbpjavkl.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhnskqwd.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gt2pmackozt.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2blintrah.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2msbcnxbf.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2wakhmcql.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gt2cltlubpe.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gt2qsqieubd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqhxvpzt.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gt2ylupkatl.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2apwngeas.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2bktzdpkg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2onfllvnp.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksfoovvq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2otzpsxxi.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2ratmqgcp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2yaufqzou.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gt2pbematti.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gt2lvnprrtc.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gt2esfrrisg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2vmrfpqga.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2kebkladh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gt2sbckniia.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gt2oubrjzng.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gt2urvmoixp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2xcwfaqbv.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2jqkcrwsa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2imbaethq.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2xwazhqiy.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gt2txqtlufi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gt2tlyaiphz.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2qzgfqfix.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2jawphlyn.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2opdzzasl.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2xieyozsd.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvibusao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2luubjsbo.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2aywuvwvw.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gt2rrrkuzdg.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2khtlcrfj.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxvqvzas.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gt2emwydcrc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gt2gkfoqqgg.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2doxvxkia.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gt2objqlyjt.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gt2nckvurny.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2xosfcrhk.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2pruimojf.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzgeszgs.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2qgkkbwwn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gt2bvcjdumb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2pbmzzroc.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2ehqscxss.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2eojbwlev.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2dhexznlh.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2qsempmcg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2kmpsimdh.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2mhvqtzsk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2dnjvrhmd.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tolecfxb.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gt2weuxnqev.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2ynodxxex.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2cvrxsrpo.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2tnolmfqg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rftujnfg.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2rbpbvjvi.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sypqyxvm.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gt2fnwfdlgs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzmhkcum.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2avgzbedm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2oskbyzro.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2lfyrvqwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2wwfqggpf.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gt2jpugdgop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gt2hpnkjevl.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gt2ktvscbwv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2blrrkauj.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gt2nztgsktq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gt2oozftqag.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2zgklgjzs.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gt2wlcfbpue.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2etkafulk.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2vrbazvuq.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2sajxfkct.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2qhmuuifl.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2hpiferyk.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2ogkmmiqu.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gt2peszcmgo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2iagbhoha.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gt2lprjicny.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gt2mvtenyed.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2stmboxvz.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2lcsetbci.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2rlrynnkc.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gt2vbzdikmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gt2numcoxkf.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2hwyzonls.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gt2jbrqbitx.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gt2lxitwsdo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjktnzmg.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gt2lcvqmhhe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gt2cpcmztoo.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gt2offvdmzx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2vlktuwzi.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2upbmwxxz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2cncxrhjf.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gt2avzslkti.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpxnurpe.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gt2cuxalrxs.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2vhesxcvz.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gt2xqifdhjl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igezqoae.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2vudlybqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2xznhmyfn.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2nvgpefrl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gt2dunbmpmg.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gt2rbpuusde.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2xiogjwvj.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2vltqccix.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gt2epeaezng.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2efteritn.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gt2bydxicym.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxojcgfx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvkkmqjo.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2hnzewstl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gt2xrzdyyje.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gt2tcjdqhyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqkvkdct.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2nhiifcyi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gt2zvyzpalk.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gt2konetcfj.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gt2sewcfkdy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gt2etkqqzxw.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gt2dgnqdvlx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2tuxeeqpo.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2dazfttyn.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gt2qaowtpwn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2icxsbxfp.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2dgkvsmwt.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2oqeemnxt.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gt2rmxvyhcn.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2vjdycrfh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2twdrbzgq.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gt2cponemtk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2yfgrzwbv.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2tqpdfsuo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2mlityzwb.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gt2eeknlxzw.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gt2qrwpeuin.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2hjirljey.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gt2omfqdcoy.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gt2bovemanr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gt2edgzomsh.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2fhwanvzp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gt2bgytdxdq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ouqvatud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gt2tcrdloty.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2eiuojepv.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2pkorrmoo.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxymlabr.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2amgnmbxz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gt2deooqhce.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2nxamwnnq.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2ugffdxgk.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2bnsnyktk.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxrglgit.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2wriytydc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gt2yaunougn.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2hsbmzhpu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2tfbdystp.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2rmbmhdle.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bawlfhsa.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjxauwfb.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2qhaayzrv.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gt2scvtcuga.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gt2xelmymlm.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2bwlexzrc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2lbzzgoox.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gt2uvtmzokw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2xrimunmz.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbluklgm.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2vdgahrda.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gt2njymcfrm.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hvyptlgz.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gt2exdljslm.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2zhawklfn.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gt2knzutjgg.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zifcfrdc.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gt2usxjqzax.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2vmslqkdl.html


<!-- 参考信息 -->