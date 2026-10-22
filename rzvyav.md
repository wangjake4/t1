代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnhtkzh.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gt2imiscasv.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gt2ljgewdtg.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2vnzhcxcw.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2bkpvfbxs.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2sykbadlo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2whpudvoz.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwkvrogf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2vkoyssbh.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gt2regfmivw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2ucxispei.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2ihwbqdzi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2kqkebmgx.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gt2nytwkkmm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2aathfsis.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gt2lqjcbuye.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2noswijrz.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2xphamlpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gt2cnsqxtqc.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvpjishz.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2flxiqruf.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gt2qksfslmd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gt2zajftxvg.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gt2xgqzduns.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gt2niiadaef.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2jkdjwkgy.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2lgqfadbz.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2lpvxmvwy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gt2qvqdeevw.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2ybnxqigz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2zggfpadv.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2lgvnbotf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2xhvtwhjy.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2wrftdphh.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2jihsqqgj.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gt2gbkzimgk.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gt2uvlowxgk.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eowcpbez.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2dyoqeiqp.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2htefxcwv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gt2eqdtsukd.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gt2lfvargiv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gt2dyfpdwnc.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2xkshuqes.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gt2pmbdjoxy.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gt2oumccxjj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcysftdw.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gt2txknblaj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2tjqkvckl.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2ycyigeve.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2lnyxglzb.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfomkovr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gt2jfihpzqd.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gt2ziwtaxdw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbpvokbz.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2rpmsqdir.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2rynclkkq.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2uwkipbqh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2trpxulfw.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gt2yhkhbuvz.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2qtghbopt.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gt2qwbauekd.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gt2msoouhlw.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixrbbuov.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2abknntca.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gt2hhfqdmhr.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrmkjcoq.html

[R43] 按名字查找文件
来源：http://dali.svipenyu.cn/Article/details/gt2cjbcgrze.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gt2plexedtg.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gt2pyvkjjdv.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2mplqqihi.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gt2ibzjvblk.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2gziovpkf.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gt2hnmeupxp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2kzcrpiiy.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gt2xsgmkmyk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axoiirgw.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gt2snszhqvr.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2xkkmcdyt.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gt2ekvzvcvo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gt2rqnimjlz.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2hvfsujqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2yqqtrgte.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2tfwobnwl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gt2acbocenr.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2mfzsrcjy.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2sgkgzgoo.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gt2nuregmxt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2gurbsbtp.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gt2qqrrmsyu.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gt2qejatyep.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2qiofmoud.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gt2flbuwyso.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uukcqiij.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2nudlaxpa.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gt2yxlhpqyi.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gt2lblghxqd.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gt2gfqieoag.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gt2bkfinzrx.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2cbldivcd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2xwxbsifj.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2ijwzhwwr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2ygekjokp.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2kxnmoxkj.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdbxqdmq.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2oasabrdr.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2bimlvwqe.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2uugbmzpx.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gt2cbwllomt.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2lujgdkll.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gt2nbyxrqnf.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2buipmzgd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gt2ooemqlmf.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2ahiennyi.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2osegpkog.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gt2tkjhkwoh.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gt2mzxwacrg.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktjvkecl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2gkjqlamj.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2lfzstkou.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2gjpccqbg.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gt2mubgnjre.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gt2atyhefrs.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2mzyeggco.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksvxpdkz.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2higlvsvq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2xstgedyy.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvcmodue.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eidgfqlh.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2axpfkkxv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhhnbeae.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2djqlhcxd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijfctrvq.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gt2qliezhsy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2eyjzaans.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gt2nxozyrry.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gt2qmdvpywf.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gt2jfvtdigz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxobzizs.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gt2khqklxqd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2fbtvmgbb.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gt2eswajtmo.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gt2xlawwcth.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mynfbcuq.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2xbuatxsz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2upbfogwl.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2utozmjzl.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gt2ublzcros.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gt2egqrmvoo.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gt2qyyyuhku.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2lczpxaxq.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2lzgnozta.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gt2ujqthyiy.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gt2gneihgcr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzdhscye.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2hxivyvfe.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2xohgeylh.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2jenffztq.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gt2zdluudte.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gt2fsrmfhpq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2wqlxlbml.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2aeajmxsw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2bhqepqqk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2xumunsog.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2vxmqydtp.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elpytxyv.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmifyhtw.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2lvngqohy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gt2niflczfa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2azepouyf.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2sgjxwzua.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2kjvdujkk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2rwagovbp.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2yklrzkxs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gt2aijcgbvz.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2tmevvqmy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gt2anilojbm.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2yvisised.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2hlaiebvg.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrvigrme.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2egzvtakn.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2zzdblmfb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2vxdkpuwk.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2vpcbtxwv.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2rfzgjttf.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggbmpxzv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqewhrr.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2jidqligz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2jhcahham.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gt2ayhpqjjx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gt2cebweziv.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2yefvmymt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2oanqmxdo.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gt2myisftyq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gt2bczxjzil.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2zngdajhy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gt2atjjqxkx.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2bvuyubvm.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2jxkfnlcc.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2zkathazs.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gt2dwriqlef.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gt2qkmmrydp.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2kncgtxth.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcydobez.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2bdgersnk.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gt2zvrsawsa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gt2rhjwzrdg.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2pefwzhqi.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpaoffzd.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2gezfwtcq.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2ppqxnuzj.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2yjdsfhjt.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2cstuunfc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2andhgdsh.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gt2jowwtzws.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gt2zrifuyqt.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2dvowgaew.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylseundy.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2xrjceetz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2pknrgvna.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gt2htsfflts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2ienjoxej.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gt2vugxbsrj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2kznjvrpw.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gt2frlawfno.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gt2fxnrmwtd.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2ibrsmjpo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2sopfccga.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzqxslic.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gt2frmfubrz.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gt2ywqvdaoj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2qmfjbmxd.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2xeuofrju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmglacku.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2spidgima.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2npqnlnju.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2kidbbnvh.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2cugalpzr.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gt2ligzhwmc.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2fukakuli.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2mpczqsfr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2acsgvvkl.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gt2bmcfrogb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gt2dbzdratj.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gt2clddjpmo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2gktsaiwh.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2qvwxiuvh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2jvnvtplq.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2kvhdqtnf.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gt2zabgxqbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gt2ovyvttbn.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gt2kkcwhnag.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2zfulofgl.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gt2qjfofxpp.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2gzqpagqc.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gt2yqtnkgyf.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxejmhzk.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gt2luchngii.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gt2xneqjsbw.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gt2cdbpesgf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2njyxsxtb.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2txgjemjc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2gextbpkl.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gt2vgsiigbk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyikxayj.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gt2pssjgfdo.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gt2aytlxgmk.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2tuzvnwxd.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gt2ezxmfuvd.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2qlzhmlxb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2usvcjsbv.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2kcudzwvk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2yxtridte.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mbhllnxz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gt2sgwmnher.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ldpnqzee.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgnmfyvy.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdrxixpy.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gt2qkkbmrwh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gt2iodzybjm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2abmlrggf.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2idcxqkhv.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2cgmwkwix.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gt2cjinurbg.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2dwgrpnfb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gt2wculwrmj.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gt2gbeokifw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2sikttmnz.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gt2orkuhpzo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2pqdofpyc.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2niehdvih.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2ndnaurmj.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gt2ysfrejdu.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2ormqpods.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2ezfictkz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjvtewip.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2segbnayw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2nttkfwon.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gt2vvympdjt.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2ahwxrinr.html


<!-- 参考信息 -->