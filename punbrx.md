代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gt2ckixmaqd.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2sftrpsqc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2pngjsygu.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gt2gbivoeax.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gt2piklcses.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2fujbnmgb.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gt2umpyumho.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2hspxremx.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2ovubjigc.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gt2mbtpungk.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2fozvwynm.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtynmfft.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzxwqaoe.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2eomxezye.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2czsloyee.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2iesssniu.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2vnxtmuqv.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2glasnkuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2ovdkwscn.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2fmaafkwe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gt2hbhayxjz.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2avwwkjfh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2xzyyfkxq.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2iyegevtm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2ultwemwo.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2tagkzvsq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2kekvqfis.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gt2lsaoxecu.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gt2qgqivwaf.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gt2eeugenvo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gt2qzecrase.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gt2gmqnhmba.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gt2aejvlcku.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2qeupkmkl.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gt2owfndoyp.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2tuybfyrl.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2halzkhkk.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2lhwlcgel.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2ypufktyy.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fepxglqj.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gt2stlcpxjb.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2exnujxhx.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnqzqovr.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2ztbbzfon.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvghdhp.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gt2fqxllegs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2zwgofcba.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2fiakukgu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2tchrigby.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2ovtkhgvw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbphdqrj.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gt2pxsxdkep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gt2sqdrutys.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2npcwxwmm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxssduqk.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gt2iolnkaav.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gt2zqqikwme.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2ezhwfbiz.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2ourtkktn.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gt2rxeebtms.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywixbotd.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gt2gsgfcqcg.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gt2caiytwkq.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2ismfegod.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gt2itdviuvx.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2kejcbtji.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2csfujbjs.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2ltshuqbk.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2hkwnxruw.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gt2ipksdukf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2milwklhk.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2ujloptny.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdkhrcb.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2xvqgdgfq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2bbjdrftv.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2fpdncyob.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gt2gzbpbyws.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gt2ufonlbfc.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gt2wbotnpob.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2bwjuvgmq.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gt2yflrnfqs.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2uloypfyt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrgkbshh.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gt2kbdogcbq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gt2uviicalx.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2hpoemyfh.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gt2yufwrkxu.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gt2otijhgnc.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2rpedkkvc.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gt2xioltvrm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gt2lwluoryu.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gt2aqlpsibe.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2miayfwql.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2xjbqfkto.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gt2kkhgpnst.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2ksxdxpju.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2qolglzmw.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2ascejxix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2iafzalkz.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2ctonymut.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2mchsrmok.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xykdbqhi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2cqcwmthn.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2qosmflrk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdgmfmkb.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gt2kgcbwjnt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2bhzzkafj.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gt2dixsffit.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2dtpshnmi.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gt2mpxzmply.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gt2otnyafrv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qltzsxqa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2frvnjrxu.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2pnotihyn.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gt2vhzhffdu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2hjvnwfxa.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2oeqgmeiy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jjtnmvue.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2sqpjndsi.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gt2swljrzdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gt2pdjikovs.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2jpmvdmdt.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2kdlokhwg.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gt2sbzpcaxr.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2jytcnhlo.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avcagfnx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2idndqtgz.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2gzlyjxzg.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gt2bzqzrgav.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2nsftwgkz.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2uwlayrxe.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2codoumew.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gt2qadhldzp.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ettsyrgq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gt2xowvabnx.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gt2slyqgibt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gt2ctyompdd.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2nqitridh.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gt2newpnyve.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2mhyuduuw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2jdtzugmh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2ghdgpwve.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2fbjdkykn.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2qprpjfzg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2htkzryee.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2sgfjtbmc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqpxrogg.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2mpzlihli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2tuuneftf.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2iwfttjbb.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gt2cibyatme.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gt2xlscercc.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gt2cgcgcumw.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2bpcedumk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sebvtono.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2lyrqxpky.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gt2pyorebel.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gt2fklwcdys.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2ekiuoqge.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gt2lxsyzxpx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2ihwnpybg.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gt2bwzbzjsb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gt2ojfvziwx.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2jbguakju.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2vypgxsqq.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2pafksnlv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gt2jwdwywbt.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gt2jksteqqq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gt2eueatuql.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2chfjjsbj.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyaehlhi.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gt2fgknuqsd.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gt2ghkyhhzb.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2gutibxcp.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znzifdpe.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gt2fpotdpnw.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gt2dvsjrpey.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gt2qgpwqycm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2vodaosnd.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2qwgspzpa.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2jdbxqqvg.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gt2ffbylgzq.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2fgwhezps.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhvaoeug.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2kxjmzprq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gt2gkurwgvl.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2ugokpxdc.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gt2elvngkbg.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gt2czgbvifk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2oxluyopo.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcqkoosp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2grpihejc.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2gqtfczdx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2bajtpowm.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gt2cwbosror.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lncynhqs.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2mutwmona.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gt2jemgwxrv.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2czwndgmf.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpbdagdi.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gt2bstvldtf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2hmftmbil.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2azejwgvv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gt2plibrlzm.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2yyimeaal.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2vgxzkpjz.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gt2hrdamlfk.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gt2mrdczyph.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gt2ohpbqiyz.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2eaxmhxyt.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2izbehada.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2ucchpmto.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2eydjgwds.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqkaseil.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gt2bnirdjfi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwphbjdi.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnpnvgyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2kqduevmp.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2eiszklxh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2gewaxpji.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2eknpeyvw.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2eaqfknjh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2jxnkhfkh.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gt2kxfjtsdf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2wohzymum.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2cfnlykcf.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gt2mhtcdbak.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gt2keraqxbr.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2zwxarrah.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2xclnfhhj.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gt2vdmjqrks.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gt2fhyuxmwg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdrfsft.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gt2karcbzpv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2dpbzgfai.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gt2rlyotdbl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2qzraqhrj.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gt2lxavoshu.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2fytnakds.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2wxwjrtta.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgmxfxni.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gt2krdjxxlm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvlydhmx.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2wjglevsk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlbnjkvk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vjdblkux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gt2ygdnogwp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2awbyouab.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2jmqrqchf.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2jqyabldp.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gt2jeyuwsic.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkmgwhjr.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2cjbghchr.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2fnqeglqu.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2jfrwftkh.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2xjywlooz.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2djllpxzp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gt2geewifnb.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2kyitebcr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2rtiinluj.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2difngmuh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2hrpgkcvd.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2bobnrvjr.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2ubzwupjw.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2mwwgkzxj.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2hyheybpj.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osurswbg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gt2dljxosxz.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gt2iibpippa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2wttyjwwh.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gt2bakekvxw.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2plwdhlib.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2qxnikpja.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gt2zlpsmota.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gt2icmgntzr.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gt2zrrzgvuh.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gt2ofnyrvmo.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gt2cruzniro.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2wozaimjk.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2ilcigdxg.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gt2mzbpkism.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gt2wbtanxcb.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2rodukhtn.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gt2ywxdswkk.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gt2eyvyafvh.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2fxzutpgg.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2wwsvjden.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gt2uupitpon.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2xmycdnaj.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gt2khuimtfl.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gt2cgucplkn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2msxsibly.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2pyofnwzn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2ytrydzqv.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2kwbblsmn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2dyfwuyke.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gt2sdgcmwfh.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkyvoyxr.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2mjumvjie.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gt2dllfjbgr.html


<!-- 参考信息 -->