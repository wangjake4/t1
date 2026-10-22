代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvtvfsvdm.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtzwpafvhs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtjyopjpeo.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtspzuxowv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtjtaehlsw.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtrsexjyym.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtszcgtkgs.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtlxxqrdsn.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtglegqlkp.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtnaukuico.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtxjumjefs.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtdtylphif.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtqowyltck.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtqqvbtbhh.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtojnwzoxi.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtafytzjhk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtzpeusauh.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtcdhqnevj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtjowshfjb.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhgsvulf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtbjhqbdln.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtpzbisbio.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtfrurxqtm.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtygmgzzzu.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gtqafzgsdx.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtxddncybi.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtgfzwmcgg.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtounhpgbw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtitfsoziy.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtuoasjncf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtnpqhxegg.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtmtdortap.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtqbivmtdz.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtlnkdoljk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtyctptmts.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtdomtkflf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtteorccnu.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtwipqxngh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtuqxhcnwm.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtlcpeqkpa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gttkcybzsi.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtccvhseck.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtcuuzpfbd.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtixayndwr.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtdydewprb.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtyxaaxzbr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpcasyqk.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtathwpnwn.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtinmnrzvz.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmishkgnk.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gtamvrughn.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtjldxfeqo.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtfuytsmno.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtxqmgvslq.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtaxycxsvn.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtncdnvopl.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtqrbozvup.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gttzxegpbq.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrwcndez.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtosylldgn.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtjvbtsfpw.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtqggqgyaf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtxhziomnk.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gthdydihzz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbntvefi.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtxrnncooa.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtcotohszi.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtzngvrxez.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gtgkuianom.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtmwwkbmuo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtmsxnxqin.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtznjcyzxl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gthuojfqzj.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtfvpqinir.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gtremsccsa.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtttyxaboj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtxyprhazx.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtsjyhsiba.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtnrnxnrmo.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gtwzpyubnf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxewrlijs.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtrwifxigk.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtdjgsgogm.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtlxhbuiqa.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtmmxnwgls.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtmxqqgdya.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtkbfszlmp.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtfbzcdvpr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtxzsphhzm.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtfpdfiqre.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gtgoczfhbk.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtshlfvyhr.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtzrcxsblo.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtpaxzgqgh.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtcbbwktyw.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtfhiawglg.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gthuhslmsa.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgtakbgq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtwubgygjt.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtehdsutof.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtyoegupmp.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtdsnhxncz.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtjoxanlin.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbbpqryo.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtwbgtzxag.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gttlnahaeg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtcfsqyndk.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtxmvusiqu.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtzzlxueuh.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtuupyjjvd.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxbumxhh.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtriszcrxx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnfcvafk.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gttotfdmfw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtxojqzino.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtrhaeeppo.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtvfxbpaba.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtkvbjzusd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtnrdfkwyf.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtxktoxpvb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gttbqqlytb.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtebfpihej.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtghsfetwd.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gthrxwwsng.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtdhkvtakj.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtxnlzvqvc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtodcqarqd.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtzwdjlpdb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtsmjbdzrx.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gtdajjglzc.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtecyathsh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtckzighci.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gthxdsyiiy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxqgenfpg.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtbkfyoihm.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgxmlpdi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzxcodgyc.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtuwzitehz.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gtfnvlzznb.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxfhvixc.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtmebywhrk.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtesojkgpm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gtsshmlhom.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtukmzzvop.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdwugghif.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtlaaayqtm.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtenioissy.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtnakehvhz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gthbjrfhxe.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtdwzifqii.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtefwoggro.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtibpmhwvx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtvfzkvmhs.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnjhptar.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gtszlostqn.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtjcqtjdlt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtdccfcvxe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtwwiqdreq.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtiivhebcm.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqcdzkxe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gttyznpmad.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gtitwmxkje.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtsrwwzrxl.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtwugdoxuf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtuqeeikug.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtmffvfkgo.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtsqcrrqli.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtkvogylbt.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtebtxvbtr.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtpmfewati.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtsxezfwip.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtzlvnqtbx.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtmkvwsayq.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtfzuzqonl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtkxsxdfch.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtogcgomaa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtruvknulw.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtyblhitaf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gthfkyqaop.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtmdtqmlkn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtzylrygan.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtodhpkdyw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpfkkvck.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtvtfsbiat.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtpomwncgj.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtgztjqjxl.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtpgxvoknw.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtyjzczelc.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtdwgiisak.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtsstfpaiu.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtjcowszly.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtjskwwskf.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtjaccumsq.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtqkcmjlfj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtwhpjguvr.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtjsvlmyux.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gtsqdrcwdw.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gtmkukfatt.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtiweksmwy.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtnnheuttp.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtnhtbecrp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtowkailud.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtmrexelop.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtkhuttvdv.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtdsxyokxv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtojlnrpwz.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtphheydly.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtxobccoop.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtbiilthph.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtkduaosiv.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtpwxthgsq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtygprrrih.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtvubwrtcg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtjbrzgjdt.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtwixuswor.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtusopaqhf.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtpkxczlus.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtjavsccfc.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gtcvnxulhl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtlphzmrct.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtlkmmbzwv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtcjygzjky.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtdxpefpfw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtmfegjtcn.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtvkkuxbcn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtuewidjku.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtcgpvxyih.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnurkxial.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtztzksxcq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtpqjftufc.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtagcefmaw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtmuyycsqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtqsmygxlw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjwcntqct.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtzvxsowwy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gttcxtyttz.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtffornrfx.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtgekgxhru.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtmzxnkfoi.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtmmxuhxte.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtrrupuqla.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtwnlootjl.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtpsxzlejp.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtmsfwrovb.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtffqvdrqh.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtloorastb.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsvgrvnj.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtupmebxik.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtohqlscrl.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtzimqgpsn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtltufsvsq.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtkguruarz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gttybacsar.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtvbfqqnqp.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtpcfckavv.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtoddcptqo.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtqjyriipf.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtwowypljc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtyaxrrtpy.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtbvffuqan.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtmubimhab.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvhmbyftd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtspaizjgo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnureoxus.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gtwrbakbqj.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtkgnhhnoy.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gttaymmrar.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtiprzdtxe.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtxlqksqgv.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtlhsfmhth.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtvogifakx.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtnzgawprk.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtmqgdyyxb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtefhrdnzc.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtdhphlsck.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtiahkntdk.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gttvtkbmpg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtbpipimui.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtviskpfxu.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtqnxgxkpo.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtkpuawegj.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllpxmzco.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtkfnmqvqr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtdupfitdr.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtveaxsirt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtevhotldb.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gthforqrwh.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtgpxltesm.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtbrftliza.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtizxqavvg.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gtksftwbyf.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtgdyzkuqc.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsklvytg.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtzllucqzm.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtzzdyllos.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtcsthhiuy.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtcsnleysn.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtycjhvqzk.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtsxdoiioa.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gtlhzrdikc.html


<!-- 参考信息 -->