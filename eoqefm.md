代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2wdnfzoey.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gt2kfkpposb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2vgvkolrw.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2verzqzyw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gt2edctkpza.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2nxouwckm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gt2wtlrgkzv.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2xjcjlbyi.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gt2bscnegzt.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gt2peqfojem.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2vwqptzbj.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krpvjbfx.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2gieukhnh.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gt2iwahrtic.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gt2ferowmdo.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2wvixeiik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2ovwelfgu.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2hdsqklna.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gt2dswrsjnt.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gt2huuuqlnk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gt2poezills.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2iiugefus.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gt2wcdaoasd.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2osuqoitn.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2xzfczwvn.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2qefncscv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gt2ipdtumjg.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2ykuqtnwz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2nspdveye.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gt2frtzrtku.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gt2npyglkqt.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gt2neyunmjv.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2teggemyx.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gt2xrcoymde.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2kmzqjrsj.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elqiwpbg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2uhwffzek.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwhrokkj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gt2aahrietm.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2sokvhpnh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2yorvhpcd.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2yvoescmz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gt2ypeuqdbk.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2zmhtavjv.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2acqnndun.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gt2jodizehh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2nsfxuqff.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gt2zmkhukap.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gt2kpyceqxe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxctbvc.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gt2elfxvcxv.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gt2ijikeoqg.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2wwaaumhg.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2kbkcxpfb.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gt2bjcdlzyb.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2djdnssib.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2tupjmeat.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugrnmuwj.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gt2yagnqwdi.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gt2rbdyajkq.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzvlfoqa.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2vealkraq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2zllxemza.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gt2pahbhxdy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouyhygaw.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2hlhfmzse.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2sowiqxzh.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gt2ztqemzcj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gt2yowzkexj.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2imzhlbvm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2nqopfuzv.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2tyuaqhag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2hgjhpzqy.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gt2khpaotfd.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2lzyloqmz.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2ymfjiajm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2gfyjlcif.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gt2unqcvedh.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gt2zteairue.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gt2zlvejuqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2dooeiyyt.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2wblufwpy.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2boahfhxg.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gt2bdwprnbn.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2srptyxee.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fhukievh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gt2qzrtvlby.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2tpyhqphq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gt2wgqspssy.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2dxijslyb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gt2bzkixesd.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gt2zdttbfph.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkdbbjt.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2qqverrdt.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gt2gcdbnmnu.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gt2sluyzmsl.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gt2wkmqjaol.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gt2lwhjtbqt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szrysznw.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opnzmdbi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gt2ofqlkmnw.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gt2wupvntfu.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gt2xdzpqnqc.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2jbkejhhr.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gt2zdtakpzj.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gt2waracfxi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gt2ngtlquji.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gt2rlqdknox.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gt2bepehwhz.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2tdjgzxvs.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gt2ctzcposs.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2djotpcza.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2novjekil.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2lbwodtqb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2xagponxh.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2fmhqgydz.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gt2lauejanr.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gt2ytvhltdu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2nwqtovbt.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gt2jucszdfp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gt2kahosfuy.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gt2yhdezduv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2lsmgzzrc.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjmslqqa.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glxunkkw.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2vncpkuoh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2vpskqfzc.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsnphrjc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gt2amdwcmaq.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2pcrhabfy.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gt2qcbymayz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ouxciyih.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2oglfomby.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sixtibzb.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ushieeof.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2ldwkwudk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gt2oxzqsafe.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2vyzwntbp.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2bsbjadom.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2ayldfkxh.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gt2hacbaxnp.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gt2wcxahzbb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gt2dwlzqxhg.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2fnmehswk.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gt2iefvyqos.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2kvfvtpqx.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2wrbruvyn.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2fpdbpaus.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gt2lckymexl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mtebinmc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2mldkdean.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtmvuihh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2mqbcnpqv.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gt2hfilzbov.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gt2dtamqckz.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2mcdmstkb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gt2lqtqxtqy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2zcmctzpv.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2bfxjbwud.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fcfztstt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2jcmtmkqd.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2frhqgwxl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gt2nuudbzew.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2aoeawbkq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2ienibblf.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2hfqhhwlf.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gt2vtdndfka.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2ylomgimt.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2bgmgxhej.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2fjrqclie.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gt2fozdicei.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbxbkfzy.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gt2yzxkmmbb.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gt2nspdgbir.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2mfuzjbuq.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2tgaiirol.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2fjyrgcwk.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gt2decrameo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gt2urxdaoln.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gt2jmpvjbrb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2bfsfkntz.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2obvkrnda.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2zizkgzxf.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gt2hnyemdfw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2vxagxrwk.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2ndbdakqs.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvfmcqhv.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2iixsccpi.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gt2vhsnrmzo.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2ididgplu.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2epstskyc.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2lghlnbhz.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2jilsqmxs.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2bnjfzjtz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gt2ndbiuxuy.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2wlfjckqv.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gt2huycwiuh.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2wbtqvigj.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gt2pecawvmq.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2wbbumudn.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gt2zaobylgm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fzlqbpxs.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2pqcadiyr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjexqre.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2xqpptdpt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gt2pdxkzbrq.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2tiqhgdax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gt2lrwoteib.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gt2jlarzjwb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhvwnsog.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gt2alpnialt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2vkkevqap.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppyjupxd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gt2lobgejea.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gt2ayobythg.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2gxuatesg.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gt2dmgxkxbj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gt2msuailuw.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gt2aupidjzy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdhihyud.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2janwkfqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2aopjcbrq.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2zqhzzukb.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2ueyzidag.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2hnbksexe.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2luqayanp.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gt2lyvzgcyi.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2mdiachgd.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2ylyskvko.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gt2mroziapi.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2utglxhdr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vdnrkxvu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gt2kcqklpji.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2xbnciidw.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2ulkmufoq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gt2enmzrpww.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gt2nbllolhn.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2rdejswhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2fuvbcqqt.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gt2tknkfedr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2jxphuznt.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gt2sdvuraob.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gt2ddmhwfoi.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2sudbxmjc.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2wvedoatr.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2rupumaot.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2gvzguctw.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2xdsqpisv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gt2ahsaagww.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gt2gwmgqyvb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2zqcusmkj.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2lwnbnyqk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2geuufcuc.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2mvjsvhhp.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gt2tgueexyu.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gt2ulgcfsng.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zeuqgoqr.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2nfnlvdpj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gt2pmvtlvwc.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2fhkkzofi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2zudwvevk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddzdtkkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2fotfdfds.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2kopcvush.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzndloet.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2sklcvxxw.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gt2qqypgxho.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2zytztyvo.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gt2pbcbuoiy.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2yddghbjq.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2updpdrfc.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gt2kbfmfjte.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gt2fvnkiujz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2acperazo.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2fknwhqlu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2alybdgoz.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2xbpaqbuk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2lgdhdoyj.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gt2vqbtytxw.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2ovktglhg.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gt2rktgegdb.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gt2nzhwreui.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qceurlly.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elgaluqh.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gt2ygqhkyyt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2gnndaxmv.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gt2zcrqxnbn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xofvwhuo.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gt2hnlufksb.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2eemdtvmt.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gt2uipnwzdg.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2bkunbnfj.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2komezcjz.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2socpfitr.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2iacobqwy.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2ooovqmqc.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gt2nqjsanwo.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2oymdxbbm.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2lzwvviwi.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gt2clrinwrh.html


<!-- 参考信息 -->