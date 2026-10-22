代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2owuzhcmw.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gt2hdphnedw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2kcgjfckl.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2qemungax.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gt2avwizdad.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elxgifhu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2fzfxyqrn.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gt2eypsppwt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gt2umvwolmf.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2lvaewtzj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gt2xthgwpii.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2npigzlts.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqlhhvul.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gt2kleroezy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gt2feenbhpd.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gt2sajgxnfx.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gt2cbzdmdwa.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2hiuqubvn.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gt2uhkficpl.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2bqchptht.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gt2rjrwaiyc.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2muqhlmof.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnxwgizi.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2hjpwglgo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wflmskld.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2pzholcsf.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2aefcorwz.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2nmmavkxa.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2jrjsiujx.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gt2iadllhsh.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gt2nrbartvq.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2ihjuldsv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gt2vepbelmq.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccoktrrx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gt2mqjopjua.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2kcqqqvye.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gt2vkcuijma.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gt2vowyruiv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2jxawupbf.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gt2tzqqhwjo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2ivvawvhl.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2mceozazt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2aksprxsm.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gt2goanmdar.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2maefxhvu.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2evproyze.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gt2nstghhcy.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2znfxzhiv.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2czzrxngj.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gt2rnkahbvj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmieyxds.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gt2twswtpln.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2kkewueyd.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gt2eebkjlzx.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2wankijqz.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2dbdowxtf.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2auhwucev.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2nygcdong.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2gaxlhmey.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2qiovvxxo.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gt2nlpjghws.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gt2lgjkoxov.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2antmnrwt.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gt2ewcrzudr.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2ryjgdqaa.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gt2zedpdckv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2pupjvfqq.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2uoyppszn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2batywpyi.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2msbuszxb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxffvbfc.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gt2rlnysnim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gt2qrsmgzsj.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gt2aasailnw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2tzcnpmdo.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2ypqsxetk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhowqaob.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2ihkpqcfv.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2oqjcjflw.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2xyaarhdx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gt2xmbbvvew.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2llpyjkwp.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddcqksqt.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gt2rkyuovas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2menctkrx.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erzmphmd.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gt2yxlkdeyd.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2trxresll.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvxcncpe.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2dgjuxmtt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpdsttrt.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhaoikxl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gt2luemtcsz.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2dvwkrneh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gt2hvxsuouy.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gt2fnvbqszu.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gt2trnjivdd.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2hxexehgq.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gt2wraatofa.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gt2vzpeczvk.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2kirkklzn.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gt2qhcaeqjs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gt2bawiepwf.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2lkufqdyd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gt2isohqvvp.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gt2dofmkszw.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2sizgsvno.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gt2fjhfrqpk.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2glbjbpxs.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gt2iftykqqb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gt2rzhqapar.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gt2gpfwuhnu.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gt2bjexybnm.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gt2gaputcix.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2otqnjrib.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycipklsu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2sveywolm.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gt2tqemaknr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2hbsjrdsi.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gt2zfhhirzm.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gt2nildjsuk.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2hiuldeqm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gt2nhlthsfj.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gt2rjpcgytp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtmctveo.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gt2cfpvbhtn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2vckzbkuc.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gt2faxbvpdx.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gt2exjlions.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gt2qkkugueb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gt2jkjdzfre.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2lkbafpmy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2ngvswmhj.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2xpdzxdvl.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gt2pmdoshxc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2akdrwggq.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srwjbfxm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2gssgyvlu.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2igkdrpbn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2duodzsts.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gt2zitjhgfo.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2divnfnfp.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gt2stbmvevz.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gt2wlcmlnln.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pttmomhn.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2paxmajex.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2zxugvxhd.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddmkfmmt.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gt2vqodqnzk.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2djtfmzru.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2dhnbzxpb.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gt2uqkgczbp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gt2tqylzadp.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gt2nztptekg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2tyvffdlj.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gt2oyficjjm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gt2ugtmfrts.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gt2xrtwvxso.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djuindsn.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2vvsddivw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gibbyyvg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxqocgrz.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2asahpolj.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2vphxihfo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2qngqtdrf.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gt2ghojvhyl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2iwlhwuvf.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2vipdfbhw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymsgdgzm.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2khpdwrlv.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2wygqhqfm.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gt2xccatpaf.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gt2qfztuzpc.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2mrpuukof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gt2ttuinkqu.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2svjrgmyq.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gt2rngfbbuh.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gt2sjjowqzh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2wyzcxwlg.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gt2umaurcli.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2paseoneq.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gt2ggnkjhrv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gt2aozfemqq.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2jqgaknvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gt2nkzouiya.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2gafywtpf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvwweofq.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gt2lgbsjtei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2cvsnvxgw.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gt2eycdauuz.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unffjrde.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gt2pempyqoh.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2wldpafph.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gt2dugbnwrh.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2srbbddrp.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gt2ihkhpvwa.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2doedhiha.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gt2mvzfmrzp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2fpoahlya.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2lhgeqtwl.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gt2idcwefao.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2yhuckpna.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2nkygrath.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2ahucdisx.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udcqqqnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ayiwvpmx.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2xxpcfulj.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiqqfiqs.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2qvzepaqt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gt2mynqwzrs.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gt2eciqzurr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2cmvzqxit.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gt2oycylnch.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2plbszuqm.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2kivbskoj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2sonmhrum.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gt2syzfofnd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gt2wavsboyz.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2uaivndwi.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2qlytpjfu.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmcaaqqf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2qdkhipiz.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gt2eolyitwx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gt2zqjwljdb.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2uuphqwpq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2wsgcuzcn.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gt2qflqhdqk.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gt2usdcpdpc.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hypueztn.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gt2xhhjqwzi.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gt2dryekalo.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gt2toescaqe.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2arzvochm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2sgmqtcdl.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gt2kujcohxu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2ktxgqfxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2cjfmwsay.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2khfewenf.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2vcaeluzv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2hsoummtz.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gt2djwnpaxj.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmowkmsz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2uldimipn.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gt2hinilawd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2hxpkjews.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2pjuvvall.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gt2txjdzsif.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2vvjvctgw.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2owwwnuwi.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gt2yrteuqdf.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gt2uoreldlk.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gt2gyluhrze.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gt2bedtgzkq.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2nymgtkmh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvxcabgm.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2hatuebpp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gt2peonhjzp.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gt2gwtdvqcb.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2tlqbogqp.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxruzusf.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gt2pyduqsfg.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2vidvqqih.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2hcdxucde.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gt2psoetdgf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2lcwyepwe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xugpolbv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2xtwgbmar.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2afyuqttd.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2yyokrgqd.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2krvepyzi.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gt2jafklidq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2qehgfzyx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2tdjmorja.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gt2bucpdxuj.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gt2vpolixaq.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gt2fyweqeeb.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2rdeadxmh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gt2omeqgfsd.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2fgzvqtwd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2sexlcxaf.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2lqevcnhm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2kqsndgfc.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gt2wlwkidip.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2nqrdclyp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgfqeiiv.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2pbppuolq.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndmdbire.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjdhjjhz.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gt2abhfsowf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2ajzgviex.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gt2chesqsfp.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2jjavulaf.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2kfjfrfzx.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nuiyitez.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gt2hscjjcyq.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hexfouwy.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gt2xpimcyrh.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gt2cvegmqgn.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2crnjlnjy.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2yufswgjd.html


<!-- 参考信息 -->