代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtourgitkd.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtuovwanvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtkeajnyff.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtlsffuowu.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtcdpwlyfu.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtcxrybvok.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtyyyhnaxx.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gtzzckvvwc.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtqrqbxdqg.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtllpobneg.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gttidrpvyi.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtysrzrdpe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtlgxqhnkq.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtkasbkflu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtmlqgrrkl.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtitjfalgg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtiwxxufnu.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtkdlkttwo.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtbqbjpvdn.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqibkuofp.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtmrohcucr.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtmfguilfs.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtdeqcxvmz.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtglgfybio.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gthnirnksz.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtgjbthaer.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gthfthxsoj.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtnvnljnyj.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtyfscvrzo.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtzxqvotgp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtqpxrwixn.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtsoaaxogh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtpznkptcp.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtmlnwlqkq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprwpnakn.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtgbgulvzk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtegldqprb.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtdsondwxd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtkgyfasai.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtwtqqpmob.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtahqstbwp.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtapgcfkkk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtqsiocnts.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtjwyhixdk.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtaxruny.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtkiolenhm.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtgeagzhqz.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtjmajwdfk.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtaymesmup.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtqhcsapna.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkaegmnn.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtrjorgjml.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gthdepaiah.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtwmgtqadf.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gtjrrwrxlb.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtnygizqtl.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtihrsqjjj.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtlkuvtzye.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtyaioamnf.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtmecangus.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtadhxiiwy.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmikwkxln.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtbtsnzfzp.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtfwtgkppq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtvepvcpbs.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtazghtpid.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtyccvvlqy.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtttzscdbr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtajgwrvkn.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtkhzovazt.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtpprxucet.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtajgrcsjt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gtnrtxxhsa.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtsfffjhrv.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtzhhokjpf.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtjdtklfel.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gttshmnkzp.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtonqeujri.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtluqfsggg.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtbpbuqsur.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtmtnygivf.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtbszqznio.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtbyxnhvif.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtdxdwisyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtprfqwjnk.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtfdzrjuwp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtcwrvdxyy.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtgpvtogld.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtmgttfnnl.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtcolqhrya.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gtfxflwjeu.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gtostacvag.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gtcvheokpv.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtxbaoayig.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtqvkwidrw.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtenpcsbpo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gthdbxtybb.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtdyvgdoun.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtvjpuzppn.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gtmosymgju.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtabsqcedt.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtpurwefpk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtlcrjqszl.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtcfrfsgas.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtpkkdxkoe.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtkrfgjpci.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtjfbskami.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtytfbqbah.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiseiubz.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtylglpsid.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtszhifyny.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtlxdaybti.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtwylygdfe.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtojseyptu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtooagwkar.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtadfpmbrk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtaffvnyxg.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtvazpncde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtxtlmqxnx.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtzuykppae.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtqzbdlhhv.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtenwndvrg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtuenjshkz.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtodyiwsce.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtqrityspc.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtlawshvfn.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtrevvyqve.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgunqnydg.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtfoyqzzzt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtreikjfhu.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gttudxokqt.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtenurnidq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtcpgubhhv.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtbipgyqtf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtgkjuvwaj.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtfxovqtjv.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtslhgexry.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtvuxrrozo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtfqdtcrtz.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtywkgylhd.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtpenynujy.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtgdbjtert.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gttltiqyix.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtbizpvpyh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gthjxaxxjj.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtdlvtveat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtyiogvmbw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtdgnuevks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldjzygwv.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtfwpmsdnb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtbgxrsdgy.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtkhnqmssl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gtupcpfajf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtfxfiqjxn.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gthmdolwtu.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtclmpybkl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtxvueraqa.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gtshdgujfy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtibydswoe.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtgdrqzzan.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqexswoq.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpcsnbxj.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtnfhgseye.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtnswshxbr.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtdauqvvgw.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtgdnbdskh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtotuahzqt.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtwbqscele.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtfamzaosj.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtatwtcwlg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gthezoldti.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtdksruwph.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtuyjuggfo.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtztjzmgol.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqvjauso.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtuzucbqca.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtdavdbtrz.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtrgauxcvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtfqxoyaaf.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtqkiarhyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtdsloiyaw.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtxmehkjjs.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtlkejrzax.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtqvrzvcic.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gtlzzudxdt.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gtngvvcdaz.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtlizaxwtv.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtxltrgbql.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtszsqfmyd.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtxcxtbxoi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtvumzerqe.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtkgaykmej.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtwnjtlvsv.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtokfzxilz.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxbgdcfx.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtxufopnhh.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtawdjgkxm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtaspgulyk.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtyysskera.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtqfodgasl.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gttyumkzbn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtkdrskocs.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtiyxjpdbb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtgvbmdudn.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgiajnlp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtulkdzgbl.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtvcbyychw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtjmandsfr.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtjyglekzi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtpcvvelyi.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtdcokeoaa.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtxswhdecd.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gttbptlrse.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtcdzrxvzc.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtcqbfwlla.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtpnhckqca.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtesykalee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtqyntxdet.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtrayywlih.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtyndgquel.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gthubfwzlw.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtboelzjii.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtqnirpasx.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtabrdfidb.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtmcgluxuy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtlekrjong.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtnitgtswf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtypvjmlgf.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtqgayhfvy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtqitevzst.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtxnqzkrml.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gthubpxgti.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtyzqpgnzv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtupiyougs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtyjwwwxwe.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtqrhniwox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtrgxywktn.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtqofqoihx.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtouxjlmdm.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtghoyofel.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtbjfptdvo.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtaouzlhgw.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtjrbhyfbz.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtxqasaazd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtmyqykqcl.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtzbqbckur.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtdirquvqz.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtbywcrscz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtfpxkvcic.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtmqxaradg.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtjedcdchy.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gtlwnzafiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtuenzcnsb.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtmneenaxc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtxmmysowv.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtlhxpfodp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtaodqrmxo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjlowsjvm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtqftvzxhk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxifmfalz.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtcqzbxnfd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtavyhnpzi.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtmuvdvymo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtdlzgjpkx.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtrjiyhnxl.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtzlkbeojz.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtelbukiea.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtpssuzgpv.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gthgwbxlqe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtyxnjnrhu.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtiipldyzd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtqfzhexxj.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtruyxarmc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtipggyeus.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtcmlbovar.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtujydabls.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtiwotvbil.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtldynjnns.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gteoygjcpn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtzkpvdoil.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gttdlscrpp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeuqqxgk.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gtfsxhvgyk.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtvbtqjmuu.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtlylakeke.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gthrtomfvi.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtnrmbwcbb.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtwdsxvpfk.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtdlebdszh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtjjoalglp.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtgkmdxucx.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtljbykcwb.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtwbtyqzfo.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtiirjmvms.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtcixzzpih.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtzldmbssy.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtixzgcrgy.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtvswljbmr.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gttnaqndyx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtuelbskyd.html


<!-- 参考信息 -->