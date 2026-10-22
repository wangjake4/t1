代发 wailian999

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gt2xklzyovu.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2xhlyocsj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gt2syhthoxd.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2mnsdugxa.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2ibcdqybu.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2wixyzkhk.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gt2rnedjrqw.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2juymfcbj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gt2xgnstujx.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2sobpbdvv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gt2rkznbrxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2nlgnwtrj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2jayxzdgf.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gt2rpvbeehv.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gt2mcqdhigh.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gt2wyglzvai.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2qfiwnhor.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gt2rlebblvv.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2kswhyfpl.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2xfbxwbpw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gt2whfbwkta.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gt2nztwlbji.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2ccdvlyps.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gt2qscjhjpm.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tazlofya.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcelhywk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2jnglsfqr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2xslplfwk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gt2qkbkulyi.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gt2ksmzuefe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2rwyauxdg.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2gaabzspf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gt2erqehild.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gt2pvtbktdf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2fnpmuekf.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2wkablwmr.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2hvekvehl.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ootgsvuj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gt2ojkbhsmt.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2etsbgzqb.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2gycortjt.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gt2feykdllt.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqqmsbyn.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2bmatttrd.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcnjaqor.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gt2witekwzl.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2gjnwjama.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2ywzitwck.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wycqhxqf.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2ufcujsfz.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gt2eldjsyqq.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gt2ixobgoao.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2dtcsghss.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gt2gjzyqauy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gt2dqafenqg.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gt2jpokavkc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2sbefqbmt.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gt2gyzsknvg.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2cbnmitly.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gt2ncogtmcj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gt2zehgjpqq.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2iqpmndfa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2trjdgdkn.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpmifnlb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gt2hllhyvdd.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2rbvvtfdw.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gt2slvybdri.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2uidmcypg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gt2dbidswho.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gt2iafdejce.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2qhbbcpui.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gt2lqrbufhz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2oqsmplwu.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gt2fltfqrnr.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2bwrurwti.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2msifedju.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2yeutfzbr.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egdqitih.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clvxwadu.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2kymkaubd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2klpseohz.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2dpnahkwt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gt2akgbbgnf.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2nprnpirp.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gt2dunnkogs.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2jgvdlakj.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2otzleggi.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gt2doxhyyqt.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2ezaxyniy.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfvkfqie.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2xvuwddrm.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gt2xnppmqni.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llquokzo.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2kokowpgq.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gt2yhheobih.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gt2mqtdiwbl.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2uhtbjecd.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gt2wpvdffxp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gt2xluohkxv.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gt2jsqtjbdd.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2odzpqtvz.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2uwcfmvuh.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2qhpwltxc.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2oyudhefg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gt2mkryfalm.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2xacfoajc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2vjpbrans.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2vatyqeis.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryoyhlya.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2pbdluqaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2maklyupg.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gt2tcnarojk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gt2xcjyttff.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gt2ishehmvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2gdzywznj.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2fslwiycs.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gt2ssrgbldy.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gt2jqmdggnu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gt2mydgldxv.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2eanfhrot.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gt2mylpfwtz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gt2rppejgka.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbxhpxj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vewymdyj.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gt2oiimlzgo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wjzvhsmg.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2nsrqgxpm.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gt2ukzxcllt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gt2ahnuyemz.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2qjswfqir.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gt2phzydihu.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2yvjfnhwh.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2rfczluoj.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gt2dnmsfddf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gt2pzdfzssm.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2hezojrfk.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2zgwbhilr.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gt2adtumcfc.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gt2cywsbefw.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gt2wciearke.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2hcbpqjrb.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gt2nyelqdxu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2gqielmpr.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2kagvyqqk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gt2mokqfqgr.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2dhigwxvl.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gt2loesinof.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2rwqvhthu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2ddeskcau.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gt2cakfnpki.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2ryxceuzr.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2bugfytbv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2sebhurwz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfziamjd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gt2rrxzfucv.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2jyxsgrar.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gt2hiivxijn.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2lgmmmtgf.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2aqkdmjms.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2hljzeejr.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2yqikfsmq.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2vcxoxtyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2awvnohfo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsunmfoo.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2aiiezvdq.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gt2vmmmjxjh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2pwgaasut.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2kfkeuqjf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2vrtqxgix.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnpjysuc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gt2tqzagivd.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gt2hojrrkiq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gt2lvzonyam.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gt2plbeptsc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gt2onlosoil.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2obwbzqhr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gt2pteobuto.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2wjvvegwl.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gt2gybikbif.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2xxwaunwk.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtbvrgih.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gt2wtpsksqe.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2ugyuejpq.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gt2injvtlky.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2swmpqrme.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2gapgtizz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2royjwybk.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gt2lfaccfkc.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gt2pkwaqotr.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gt2dwthzksi.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gt2wprkothk.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2qsaxxskz.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gt2qflatncv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qjgodltk.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2lufsmjsh.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnkhwjyo.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gt2egxplrus.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2luqccsig.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gt2ltutxter.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvdfgcmr.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gt2ykwmssyt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzhokhtz.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2kiklqrnk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2vysddiyr.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2diwbedyj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2kmixludu.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2qwdyhbny.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gt2kxzckesu.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gt2kpccvfui.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gt2xohevlsv.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gt2ptrsjmrp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2exhppbft.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2oumpoyhq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gt2bdudgwbt.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2cihcynor.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gt2tksfnugq.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gt2johcctlm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2nmrxshis.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gt2afkpsyfn.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2gtljzuxs.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfwszxfy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2xzpubyjf.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gt2jpotqvlr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2utpjeroq.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gt2kgfduseo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2dxmaheiu.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2pxkjdcxr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2stonlpkd.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gt2gyvodmrz.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xcngtbwa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2jjfekwad.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gt2ehvscosp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2dazwzndk.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmgkoyat.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2akfsaxxo.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2gqjgpjzw.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gt2omzuvwex.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtwhbatf.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gt2mzwmqach.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljesyymp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2ntphzvqz.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gt2xommqnqx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gt2szfbulfg.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gt2haowoliu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruevzawm.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gt2iqiqjqby.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2wjyusjgu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgzlkad.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gt2lqxryvae.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2gfirguah.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2odofrxvz.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2ccqlxpwn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2xzwvnzii.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zknahszd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gt2yfbbnrhb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qfcjfvaf.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2zqsbaxvk.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyhqlvhn.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gt2fhujmtpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2vistjlbq.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gt2vrtgpghb.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2xuyjrlez.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gt2btapuquj.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2eceacsqe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2ctjmouqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2xadqjlff.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gt2gagbtbuo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2klrnhsyg.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyinsttg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gt2hoenvcta.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gt2znxpcwmp.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymsygwcb.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gt2bajeohoq.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gt2irxgmclk.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgdxiqiz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2kqzasfxy.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gt2vbykdobj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2xpfkbpnj.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gt2xwwifrab.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2jikxhzpz.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2pmnnlmkv.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gt2jehtstpw.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gt2yqjgwbfa.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2izxgmanh.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gt2snkprtwe.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2kytqahli.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2cpchpwuc.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2lkbhczku.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfrrmnrq.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2qocaimky.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2cygzmmsc.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2uktwvjad.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2ghxvxizy.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2ytdkbzii.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gt2fdpaypma.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gt2qhxhtpfb.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gt2dsezfnmx.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gt2jvadkvmu.html

[T22] Swift：字典
来源：http://dali.mhx1999.top/Article/details/gt2mvgdawfc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2btnauekk.html


<!-- 参考信息 -->