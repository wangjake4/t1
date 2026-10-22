代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gt2ozkqicwo.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gt2dmkllsmm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2rbqgamwh.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gt2xizhqeoy.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2vwtetije.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gt2cdhkcdvn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2xfsbxcjj.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2ctmzzsna.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gt2zdneqcqv.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2rylmmstc.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2elaxksaj.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2zexzdkaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2dxidrpbm.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2kgbvqgbx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2ihtknazy.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gt2wsctihtd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gt2aiippexp.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2telwvlld.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2tgxkkzxs.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gt2uwgyilwr.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gt2nuuwdvlr.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gt2wxjcjflk.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gt2sbfalhpp.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2iwdojtpr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwlqgeoa.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gt2obtjlowz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2vzibzryh.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2qpddjgyn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2azbpracy.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2kyyyblpv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2dieiqdao.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2vvfzkcqm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gt2mjbioebh.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2dlapqzwo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2kribdzxw.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gt2hbrxmfne.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bykfavxs.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpgrhths.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gt2agogezlq.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gt2cuoapnhy.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2mxdudxcj.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gt2mdiljvea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2yeclfkfy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsgwkjmp.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2xzxrijfn.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gt2qlmozpjb.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gt2pctqcvnt.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2kvxxwpuv.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sksjzoxt.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gt2vycirffn.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2nemmsvtc.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gt2kzfsmdnr.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gt2ampcalwb.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gt2agbtvqwl.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gt2tgxqgohg.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2pdjkjlit.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gt2sfwvmpos.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gt2kjkhdvsi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2etieixjz.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2tqezgwmf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gt2vgdztefe.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gt2bveekwjk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2hutbblok.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2vxtjvvxp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gt2utqgotyc.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gt2yfkehobz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psjssivd.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnzazusv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gt2aioexuht.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2fmvcyqmf.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2zabvysnw.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2ggjgansx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2basncwbx.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2ivupmaau.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gt2plswrozc.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2oxsmjmqh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gt2waqekwtz.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2jwpkzoaz.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gt2nhzgcvuw.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gt2atxfldow.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gt2hvcecglc.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gt2gbewnlva.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsvgdpxb.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2otkixsbm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gt2fbssrgxf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2noyjdgau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2chkwvuzf.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gt2tjqfkhoj.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2xjugdldz.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gt2jchlgnzu.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2tcitqolc.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gt2yvgmepxw.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2qfnizuue.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gt2qzvmbygy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsxdzkcr.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2uisjvzjh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gt2tnsldbvm.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2encwghgh.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2kgwuzywf.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2gvdnpiwc.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2ijegpecv.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gt2kfpjbale.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcllmuqt.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfhyfbxr.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gt2fvwvukgg.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2ketgcita.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2ugrbqqzj.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2jnyxhcbg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2dnyivevm.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2evnadbft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2erqwzzko.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2jtdjdviu.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2dgysocqc.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gt2dpmhlxtb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gt2wxdcdkad.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2gvxizqov.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvgniyuq.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gchqlpqs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2miahvpvv.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gt2rzdfmfcz.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gt2tbblxett.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2bgpjpgne.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2vhlaacew.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gt2ndgisydi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gt2vzfthhnm.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2aqpvryvx.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2tlrhsath.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rhydhvfs.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2obhzgkyr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tteueepa.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2ferqubag.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2rvnskmmx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2iqpahddy.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2nnyvjjgd.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2ghsmyzfd.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gt2ihkxvvim.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2luzlyawq.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2gafjyooj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2lqfvehfu.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2imvlfxze.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztxuijms.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebovclkl.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2iqfnakck.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gt2krootbib.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkjsxizs.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2ovaoouzd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uefewsmg.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gt2vzfulfem.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gt2brhpanxr.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2jzpifmwe.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2mnbksbya.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2gwifhzqc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2zrjsfswa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvtwjxcq.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2rxopfdic.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2ghcnhbmq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2uabyssav.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2ptkbjysq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2dtxfltfu.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2ljtytbgg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2feqibgxa.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2tzjuruyn.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2trqgxqdj.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gt2ajjzjyok.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gt2owgyxxvj.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2pzqatavy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2fnfgldmo.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gt2wcdacaws.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2cywtslkf.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nemvhhlf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2yratcbsx.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gt2dtgvstrf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2vlfpmsaq.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwccmqet.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gt2ixunjhlo.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2lduhtqld.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2vcsxnogp.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gt2asoqnznn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gt2ktvleghb.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkwsjkyw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cadtjaot.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2bkgdcnhl.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gt2gngncavv.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2tfuawstf.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpietggr.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2oenfxprd.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2okublebn.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2evedzwdz.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2svqwhtzr.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2fmdhmaxt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gt2kvshoclr.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2jgopzqag.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2vntzqujc.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gt2uxtgdlya.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2djpgbfwa.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2olbytqyh.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gt2qwfawrja.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2otvijjnw.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gt2zyabifgv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgihgheu.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gt2frbvwjyt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gt2wruyfqkk.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2zdhmeggl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nteeiwba.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2ktddlwan.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqfxppor.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gt2mlqpyaeg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yonridrt.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2uqbnowgj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cffeqyrw.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2uhdnlmsi.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2xqvlcmpd.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gt2tordfboa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gt2ecqsygnt.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2pepfrpxp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gt2oxrempwi.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2nlxuihil.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2ezxstcgh.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwoidmmj.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gt2msfhfycz.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gt2leqeuasn.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2vhkmvfbn.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gt2tcguxnhe.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gt2ducvmlvy.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gt2ujngukrt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2tijfdljy.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2ngeaeuec.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gt2thrhkphs.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2aesptrvr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gt2vqqmpqxp.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2gcyxkanc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gt2lnncbjva.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gt2kglfxiqu.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2mhvgfttf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gt2pumjohln.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2unbikcmh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ampimruh.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2fhfmuumb.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gt2yjsouuti.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2rjoqjlis.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gt2yetczfxo.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gt2xjugzapo.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqyrpfmh.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2pwmvqnhf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gt2yniaiuwb.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2xcvwgtqt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gt2apozlrks.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gt2oevihyda.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gt2turguyda.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gt2gzfxlmoo.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gt2nzaocffu.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gt2rwceoubt.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2utbbduus.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gt2tpynapzr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2olqqwanq.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywymshzl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2fngkhicf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mgdprfco.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gt2jurosgov.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2isfvjgax.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2jkibbpfo.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ueumqoni.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2adqnnufa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gt2vkggbhvb.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gt2wgcermef.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2sxnnhwkb.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2netcdvab.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gt2wnafcupz.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2jydmmafb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gt2qvzbmyno.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twyqncwr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2zkkvhdkl.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2qpyqrpyc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gt2cuhmknut.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gt2qwlceddf.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2mphzruef.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gt2ltezwfqt.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gt2vzrtwkqu.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gt2qlpvodpw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gt2hgaxnmrd.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gt2teeeebmv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gt2omwfdvjz.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2gcolfcvh.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2eqezagam.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gt2lqacjazv.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gt2cpqedwjg.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwvsytaq.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2dyohpkde.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkpgvj.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwgmwymm.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2mnqoevbq.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2rkzwdakn.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2fslwmhfv.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2prmuuwoo.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2etskcpej.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gt2umwjhzli.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gt2wguuussb.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2alzawvvp.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2wtzvqafi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gt2iclbxepl.html


<!-- 参考信息 -->