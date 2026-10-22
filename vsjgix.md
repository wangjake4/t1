代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2ujoyjpyj.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2vjvtwvqg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2knadpmln.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gt2scwiejzs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2oblqfhtr.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2ogsqmrqk.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkwyzdra.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2rkbxaaij.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gt2wbyfepdl.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2bufbzfho.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gt2kvrawiyd.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orvpluzd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaudvqba.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2waipuzhh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gt2lspyfazp.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2xtsmyyvn.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxastbzk.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2zephvesl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2skmyfbiv.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2rjfwprhm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2igghyqkl.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gt2yccdolsh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2tiqvxdcc.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gt2qphvqpbv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gt2lsbmmrfq.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktaofxin.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gt2ymalrhxp.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gt2tbjhswvk.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gt2ozndegvm.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2jgnawhxu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gt2miuetgrm.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gt2gyovjqyz.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2gljkvpfv.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gt2rtndetha.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gt2dbzyaoar.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gt2fgvshpsy.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2vmezzhxe.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2vpyjbgiy.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkgoofdz.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gt2rmyxiqwd.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2qebjnhbd.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gt2agebeoyx.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gt2svuoihsf.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gt2ljamozos.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gt2qxzhglss.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gt2aaolqtxf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gt2bmockbzh.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2qsqguwfx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2lqlcseht.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2ezydhtmu.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtcwzyxk.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2tneolkqf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2sfdgnrgu.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2pqvxcbih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2helpeemu.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2nhuhqugy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gt2kcydheir.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gt2okprhayt.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2acaljcnr.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2rbuhtkwu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gt2xtmuvfhn.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2xxthgkmi.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gt2srefaxuu.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvulkuwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2krljkbkw.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khpgapvh.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2lqfncesj.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gt2llidkrlk.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2dnxqdduo.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2ybzlchsq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqqhwbts.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2ibpuqenp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gt2edcknxcv.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2jhbegojn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhjzjtnc.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2olhyzjsb.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gt2lxfxlgeb.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2cosnytmg.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcynfrib.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gt2xwgxzxjg.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2tvgitnep.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gt2gowmksdn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gt2uggupshs.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2rffsurts.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gt2azpmnlkc.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2smlbejov.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2vlzsqzph.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gt2hwhbhavz.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2chtkjllj.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gt2gxqeqyrr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ckmeztng.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gt2cnmvgzwp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gt2mujurdmp.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gt2chbopfdr.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gt2yhsjwrvu.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2ndmgmggv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gt2hfgiltfb.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2ebtjbrju.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2szftihzg.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gt2kvvvzehp.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2qlezdhcn.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2tggxqncx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2hpigaite.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqfvfkbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2xwawdrjn.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gt2azdhuosf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gt2glhklake.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jggjlubd.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2qevspchb.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gt2hrqefosa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gt2xnpdkwum.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gt2cquzktxq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2udapuzpm.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2ofehgwsa.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gt2fclqcrly.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jgcozlkr.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2ucjczkox.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2yuiwbnqp.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2kxdsevbo.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gt2zhkwrntk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gfzjeegi.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2utblifop.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gt2ijqkcefl.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfwdjpxp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgueoxl.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2ldcerecw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2uaxavfsl.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2mnovuuis.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjzyryec.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2udxxsflj.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gt2khhbomkm.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2lotnwrpx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gt2zypuyjti.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2vwvxpldr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rceovzal.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gt2rpncqsnu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gt2necxztqd.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2aacqwfnm.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztsaujbl.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2hocxlypd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaxogzig.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2adpqhkcy.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miuzukvz.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2jzoilnwk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iskgdnxv.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gt2snknxdwa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gt2bxhzikjx.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygpauxoe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2wloqanht.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2hoyzwlia.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gt2zxonuknn.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gt2vsewqgxw.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2ufvkvrwm.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2beaspmlw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gt2ablcjwjn.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2miiafyzh.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2srrcqeqg.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gt2oviubkrj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygneamws.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2qcjfiqrh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2yhumycfo.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2umelmjam.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlvkmrtu.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjquzwli.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gt2dctgeeer.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2jhsxleop.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2dydcbqda.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gt2pmbfalzr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gt2udatmdbs.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gt2hrkanuis.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gt2lmrvvfcv.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gt2qtfnbllr.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gt2jdeuvsol.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2nbxmivny.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2wkobholv.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxxllbut.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gt2mltjhhkj.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvubvjyw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2tdmatxyr.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvnhvyfj.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2yfvuidnl.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gt2eezncxhf.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrrqtswy.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwjjguwl.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gt2nmbmntqj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2dyxghras.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2ugrtqksx.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2npwznhlv.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gt2pohuqkyl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gt2fsemzuex.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gt2ufatumha.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gt2ljiyloks.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2drtllemq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2jpoygrqo.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2zttnfbql.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2vcbhhgbd.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2zacxhjxw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2fkcysbjk.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2hevmtggn.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2kwqaxgls.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2hupislyw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2tpyspwis.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gt2qnezxfvq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2eupsaamp.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xphxpjaf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gt2kwksqvew.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2qzqbqiqy.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klxmtzco.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gt2asydqtvm.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gt2clyttztt.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2ucfykvqd.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtzxvysp.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gt2eritzbgr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2biwizqjm.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gt2cngeolrn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2uyzacqnp.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gt2yckjezvb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gt2dbqhqjah.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2vyppkhup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gt2tycgovis.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2mswbpfhg.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hogemqxx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gt2jbqjupfc.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gt2yegjgsru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2fbibazpt.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gt2merqduwp.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gt2qibulpka.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gt2uuwauwel.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjrrvvmw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrqamrj.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gt2jpwmumom.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gt2fhardcsd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2nxjjrkrc.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcsqucmx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gt2iwskpirl.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2ltgutfyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovunidtu.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gt2krpqrlmb.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gt2dukrnuea.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2bbdlparb.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gt2iwrjhmia.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gt2lcvrhdhz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2fnnsivij.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gt2udquuglp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2modxftox.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2sdyrymnt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gt2jtylmjzy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2oznuknsm.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2ylrowtku.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsxuiqml.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2yxrpoxyn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2ohaliopd.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2cdkxktqa.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2lrarrpfo.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2dzipfzbh.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wglvhswl.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2erenhxaf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gt2usmxomux.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2rgnhgfpr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2kczpqoyr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2izyyrrqt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xczyqqyl.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2czujwwro.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2vsspmaqu.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2ckdacchb.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cngdnvgu.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2lybwjmbp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2pmkqrshp.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gt2eiekinzf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gt2lrzozbxr.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gt2nbarfjut.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2vazasmka.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gt2knqamfvy.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gt2uxapmbdz.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gt2zvfwvhmy.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2ikinedor.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2bwnmyhmt.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmcwxzly.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gt2cffnibva.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2pzqqlacp.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gt2mgljmfdq.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2kgayqjuj.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2fzzlnxdn.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxvpboqm.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gt2pxypircv.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2pwlnhnsc.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gt2gtjolgda.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2swofrgev.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gt2xxwpttly.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2qtsymgmn.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gt2pmezsbzn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owrpmwsq.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2odelvbsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2tkjwwjtu.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iaodystb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2jpixecik.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gt2bwentgxf.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjrlwtpd.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gt2vehwnvsj.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gt2ewlowoeh.html


<!-- 参考信息 -->