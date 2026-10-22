代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilkxegzk.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gt2csuhzmly.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gt2mowfgndf.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2pifcuszc.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2bzbepail.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gt2vuxbkzcp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stzeawlb.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2cbmjkpwf.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhbtaiuv.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2yctambwm.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gt2xdyziuqy.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2kdjwxmnk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gt2jlgwcvvs.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tetaopyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2jrrmnvel.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gt2ksfpcxxx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gt2lujjneaa.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2jsmlkivh.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gt2ornmwkai.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2xeqrbdgn.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gt2rzbfofyx.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2srnwvfsw.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2bgfzlsjn.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhnxydor.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2pakufwil.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2klkevzlk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2juysogeq.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2gbqeahnm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gt2pfeugvqu.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwspoxdf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2gfbwdmks.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gt2lsegthmf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2iukjwiea.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2qeqorlts.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2mwsifiwp.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gt2hpelmkwh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gt2qcobcitn.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gt2xkckhntd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnfztrml.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gt2tmdyefwi.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gt2ldctbaen.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2eieostix.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gt2pknzidvd.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gt2toagjeje.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2affnqpny.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2aundedex.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcqywkvk.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gt2vpootuvm.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2ivvsqgfy.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gt2prwlpvck.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2troercav.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gt2iohawsjk.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2bwkzjgjq.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gt2sblgkacg.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gt2woqstudc.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gt2wonnbukm.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvvppehy.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2tlovbixn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gt2iluuiteh.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2rsszrhnn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2btfmdetg.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gt2zutskytf.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brwtbemf.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gt2owcjdsyv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2ycurpeuk.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gt2qcrjjmra.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2nsudqnqh.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gt2ehwzcurw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2mirsatuc.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gt2caaemhhc.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gt2fbkujetm.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gt2unmluiod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gt2bhmwfwoj.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuwizeac.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gt2fkjznkwu.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2zccxzwjp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2navbmrwp.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gt2uwfeqwoj.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gt2zootzlco.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gt2nfzlxeul.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2fbulvlto.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2qnequdyk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2eqqbdgeu.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2gvnjxwuh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gt2efchmsxg.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2srgtikng.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gt2tismraur.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuljsdzi.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2hmhmuzie.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gt2kuzcfabd.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gt2xwpzdoej.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gt2webofirt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gt2mbflwlfs.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gt2oszutlbc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gt2dwvqtfxm.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2udqdxgfp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gt2vteygjve.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2sbqrezfs.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gt2xjyykngg.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gt2dchiywhx.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2spadmrdu.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2ekjapvuh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gt2ytrpuufn.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gt2kgkvolnq.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gt2erzfmecu.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2hmzqgwyl.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2bpzqcnea.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2elsynojq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gt2zgkhuquh.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gt2ojnhzxby.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2stoflmga.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2reotiagf.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gt2tfulllsx.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gt2casyxykj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2uugutjrx.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gt2txxbudjc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2dsfafoac.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2yofpnrfs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gt2ozsknavj.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2pxkwbqrd.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gt2srmgvkac.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gt2leertyro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2gjjrxhjt.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gt2dgaxbzlz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gt2zlrmjwwk.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gt2sfqkfijq.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2imldqcrf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zlivwpkv.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2zxwpfwou.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ylolgrlp.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agtibwna.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2cjuxspve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2itqzqekh.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2abierqjx.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gt2ldpgphac.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2gygxggcy.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aevxvbls.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2titzmvyn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2qovgunep.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gt2saewzyax.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gt2twecwdml.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2wayrbver.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gt2gjkruoug.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfebcuwy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gt2eegxtnis.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gt2nuknwcts.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gt2baounsmj.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gt2ldnkhrlv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2amrohlvq.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gt2icfqrilv.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npaxmkrl.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2oymqzlsv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2sdeuiiat.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2wqmeaxbp.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2gxnanplf.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2ljybhoex.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2sjekichg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxxqpaf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gt2qmepradg.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2ezouqgdg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gt2zlreivmx.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2kicormpw.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2ibsuujnj.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2mfscrbhw.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2odnbgzyx.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2qojvkics.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gt2xwlczduj.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2texzkitw.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2xzyjgrry.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gt2wibpkwca.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2mqjlvmsb.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gt2npsalbdl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2mcybbkbm.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gt2cmnjfuhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wthweazt.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2vxcvtwkv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2jrqwyhqy.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gt2irycynde.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsgrjuqq.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2jcyoioxg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2qqmstpaa.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2dnrygyia.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2nqbbycil.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gt2ruhdghta.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2bpzhbgga.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2sejcwyrq.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2feqhwped.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gt2fbsuxugv.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gt2menutvro.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gt2pubijiuk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gt2kaacocld.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2dhoxmnit.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gt2utgsqxxw.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2eqyofhqv.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztqkvalr.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2nhkdkvtq.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2wkutufxp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gt2uebvebme.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2nhwairwk.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gt2kauhzirg.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gt2paskyvob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2zurdwwpg.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gt2kjlxebxd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gt2ptlvyuqf.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2mitkvjui.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2evuvgpua.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgtsusfu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2mysuaxzs.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2lcovghpa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vecljste.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2nyfjtkff.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2tvmmgtlk.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2qefpfuor.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gt2twockvhp.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2fwkmbxvu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2uhyuxdos.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gt2qlnrxwxs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2rfszzhqz.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2mznukshq.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2bqoccnqi.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gt2qirdjaae.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2frkxpfay.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2vggemaqe.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gt2knricwuv.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gt2jkjjzakm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gt2jshyldaz.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2gggiphrm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxyoczvk.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tebiplcd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2pttujqle.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2saugsuti.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2izqcisoe.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2kesvflne.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2rppobgfn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gt2glwfbzri.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gt2mptrspis.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2tyadqsrv.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqrgmhrz.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2aelgkntm.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gt2aevgrhcj.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gt2vjlrkycr.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2aioyvala.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gt2ypvaacoo.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2zkmcqkde.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gt2ybauxeft.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvapcdvz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2mcfdiumd.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gt2aezfojac.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gt2ulrmwwjv.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gt2imjbvuee.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gt2feyvuvhr.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2xezmkmys.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2dtqnvclc.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2jjstgorx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gt2rkyrtyjh.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2gjrsvcgv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2vhcfavji.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dqcpndyd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2dqtbvvui.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2qtnkxrhv.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvjhykmm.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2kfjkyggm.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gt2wxgpfeos.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gt2pjbzafxg.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gt2nlgiomiv.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2whqipbwe.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztunxvpe.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2hqdbnysv.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2ijodxokk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2gsukchiy.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2rupufalh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2qxpmdtbw.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2grigtyes.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvjecbsq.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gt2zjczndro.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2jehbfqka.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2asnzcjvp.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gt2zwehcmvd.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2lzzpbpwk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gt2lxuoszqo.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gt2trktvxtz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gt2uvebwovd.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gt2fowzxmvp.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2azurtoqe.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gt2wzsoypjs.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2nzwevega.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gt2pteerkqv.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2nughvsad.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gt2hcktgksk.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2uuyhcyrx.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gt2nsbvsbzt.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2mjnfezwu.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gt2vflfezez.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqhmmost.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2zfssfkao.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gt2mshkerky.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmdptxpc.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gt2dpagydmj.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gt2snuqtqrg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2aeiozkvx.html


<!-- 参考信息 -->