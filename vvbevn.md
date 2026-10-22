代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfepdrxp.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2zjvukljd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2nfuffkiv.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2njlghota.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpeyuwuq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2opovowvn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2lcrmdtir.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2fccktsvw.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2rabtlwcn.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gt2moruycfe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkvxofee.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2ojfsuvle.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gt2bfnzyqjb.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2vuennuka.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quwyousz.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2dthaaxdw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2wiufwigk.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjuxpeiv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2mxccmyic.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2htwwnoho.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gt2vntutjnj.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gt2mtgwgjul.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2oeqwdxzp.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gt2hwpzjzlb.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gt2iaydxlom.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gt2axwlfyax.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2dsvajhbz.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gt2fwmpegpj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2ziyimycz.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnvnhapr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxatspvw.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2crolmafr.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2hztylrho.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gt2zbgcrmoa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2mayvcpyf.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2ghdebafd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gt2vlbyzhkj.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2gcknjoqb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gt2rxjebkfs.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gt2lupjhljb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gt2jqcemdvh.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2lzngymep.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2balbohyd.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2dlnmdgoc.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2sgsqzuxm.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gt2ecpghhhu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2uhybkxxa.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2vxubcxqo.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2aybqhzlu.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gt2utskguby.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkcinvgy.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gt2upysaijs.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2fxlyeopx.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2nwgmjcel.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gt2korzibhp.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gt2mzmwpjgz.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2odaciafy.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gt2fggbfzqk.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2tcelctxd.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gt2shfhmujv.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gt2zlfjlcwc.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gt2umtcsikl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2jxzdbise.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gt2noaugucz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2xoxxevza.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbafnsid.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2lgnjqprx.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2ikysfizi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gt2tzwznyqv.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2ysbpmwln.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2smwmdlan.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gt2grhkxatc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gt2awgnihbe.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2reazwwsg.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2rpfyrmri.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2olawiqos.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2roljdxcd.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gt2yiudtbgq.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2yfhclwzd.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gt2jpjngcyf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gt2jycrvbls.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2rkindzck.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gt2zkxwjcmw.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2viddldlj.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2napvevej.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2oodmonyx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2maeyprvo.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2dgnfubjp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2sdgdyzgp.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2stiawbre.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2obkzmemf.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gt2tjwottym.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gt2xvmjfcyn.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vemictaq.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2vhvbpucj.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gt2joxjprzv.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2oauymtmk.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gt2dmmtxciq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gt2qphxroqm.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gt2npzjjkia.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gt2wfkzblyv.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnixfcoz.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gt2jtpkxkam.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gt2hkwxjkva.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gt2foaohiub.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gt2nogbbzfp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlrxtnp.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gt2lclqotmi.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2rpabmznf.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2ambdwdyr.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2jprcctra.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2fsafvrep.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gt2gdzqobkf.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2qnfqtzmh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2ztbylnay.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2opmjjsrw.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gt2xmjnjyvm.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2ewmyppgv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2nxfwuojo.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2wmpywnfs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gt2epqzheya.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gt2jjeyttmc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2ndsxsxjy.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2vvrnilrv.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2kccpaayd.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gt2skkflcbo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gt2esghccjv.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gt2horgkolr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2lixekajw.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2rkgrsupp.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gt2uwnfwdig.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2jlvpjjak.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gt2fnroonpq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yumtuerv.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2yutnyjud.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2mvsfwaek.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2kjpjmdva.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2kjdmzshu.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgfqyvbj.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxddafsh.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gt2ofalgpvg.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gt2tievaalt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gt2prxloybc.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2aiglfdgc.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2vaazmnba.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2kzkdurrn.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2erngcwhk.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gt2naxumbos.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2bicwxmbx.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzbvtnob.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gt2bevemeal.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2hgdnekgg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gt2geyfzjce.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gt2wodzqiqh.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dogyiatg.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2wzbkybrh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gt2nanvasik.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2rrfugxjv.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2xffajtlv.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdzryvfn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2yccvnvre.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gt2ydlziwbm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gt2kcalrlfl.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oymaoohk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2cirsmmae.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gt2sesddyav.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqhlvyzc.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gt2fcvoxzkp.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2uwseycop.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2hfixmiab.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zejjielb.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2krzkmkal.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzawsgjr.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gt2uzkcmrmf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2kktojleh.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gt2owxwklse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2vtusyjxu.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gt2jtaxfism.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gt2qfjyaunc.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2ywlxyivj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gt2vugotvdi.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2zfkqgyze.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2vbaursao.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gt2ccmaazgn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gt2gnfygynt.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufgrnoea.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gt2optlonvy.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2saedttzh.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhrrrcxl.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gt2toclhrxg.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2ofohnynd.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2qklzryva.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gt2pxvxchhw.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gt2wzpjphxl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gt2hhbucjfk.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gt2hhesoueb.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2fptpkpbx.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2hlsptdcr.html

#endif
来源：http://dali.andypj.xyz/Article/details/gt2ilnopkzd.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2sxqlqdpo.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gt2slmnzndh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsgojsmn.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gt2bkaoflgx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2rithqscp.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gt2wbcaevaj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gt2qzgjbmil.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjpoipgh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2yovovjww.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcnonkal.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2nturompc.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gt2oaobgllz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2plwziswb.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gt2snrmlyim.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2qacmrnyv.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gt2xzdnorpd.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2eejgyukm.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gt2xjmfnfhx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gt2yehvitzf.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gt2lwuacdkk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2nxkhcfgb.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gt2ptolxeee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gt2bljidkxn.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gt2qwhrrgsu.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2qpmtniss.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gt2tjsdbxut.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ppqqknor.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2lvhsxgac.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2ebxjvvoy.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gt2rmhvfdkd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gt2taqtnbic.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2aobrjhjx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2xpdyayuu.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2nsbfpoku.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2epkrapgc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmgtbrz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gt2aidfschq.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2hqjabhtk.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2dmxhzgce.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gt2nrvrysux.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2wostpvme.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2qspffqqx.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2widfvkyl.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gt2fkgjpgma.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2phrqtrwq.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2dzjnqqsz.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gt2jufdefsj.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gt2mntyhqfi.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2ecflugov.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2vdeqlbge.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gt2bkpxteak.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugovrojz.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gt2nyhicgvn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gt2cslygoka.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2fauyrzva.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2iokogddb.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxlyyptn.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gt2whxufixl.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2dqpdymel.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gt2xaqdjreo.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2rspjhusb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgwapzug.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2unpdwlvs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gt2fquibprh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fmbcvevj.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2qsapcahx.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2tdknlyws.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gt2gcfycndc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gt2dbygyfyi.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gt2hpdsvahx.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2iremozze.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2cztaimes.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gt2xnhnxeil.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gt2ijuicrzx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2jdhukctg.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2cvpnrsgh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2zdscjgpo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2ybowdmce.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2opmunoxf.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gt2cohueein.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2mxojhiul.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2cvxeepch.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrinrpun.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gt2ofczuohv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xojvzext.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gt2nqbckuqv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdwqqmvs.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gt2bsdjivlh.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2wjoqciun.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2puswnpyz.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gt2butemijy.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2cpnsvgvy.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gt2bmvaewyq.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gt2xbymzidz.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gt2gzngpqkk.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2gqcgrrcl.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2totomywi.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gt2mxdgjcwc.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gt2oitupdem.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2cdsxbvqv.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gt2mzxrtbff.html


<!-- 参考信息 -->