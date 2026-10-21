代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtqordkxqn.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtjuryddqs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtkfdxyvjd.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gttxallhht.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtcpqqljij.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtkzwzffqp.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtfremzrmt.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtmpermtcb.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtgvvizlqw.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtsqfzcero.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtxlmpnear.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtjvoekerb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtxvjtnobq.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtgvjizoxm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtvhzhxojc.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtymfmbnmx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtxmuoebfy.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gteyxopnno.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtmcxqnmzz.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gtgcosuysh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gthpaqvbac.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtxywqvltu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtiscrgamk.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtjaigtbdg.html

echo "${#arr[@]}"
来源：http://dali.cheryme.top/Article/details/gtspwxxudx.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtzhrybmvj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtojaxhajp.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtfkhljazv.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtaltiojcg.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyeadvns.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gthnngxatp.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtxybzckds.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtthtjaecy.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtxhdvjwvt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gthbolyesj.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtlpkxbysj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtpdfmvtqa.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtvgdqbvia.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtaagzykfc.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtzwzabzzm.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtrlosskeu.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyemspzwh.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtnrokbjhz.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtdgluuneb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtspkpimac.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtdmgyoaog.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtqmaegqtu.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtbjcyouwx.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtzkpfctuv.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtvkpepjil.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtffkgglsd.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtvifjuinu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtxqtjduzk.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gtkkvoyhzd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtpdmzilay.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtoswiuutt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtkylszxhn.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtxwgyirsm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtjpiixhxj.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gttsublpmd.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtdbiqxvxh.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtlarpfeax.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtroifbpdm.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtpdgafmgf.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtxkggrjkt.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtkwjrzxsw.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtiidyjulx.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtqminznlx.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gthxjyjmux.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtotnjxyev.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtsdbmqtwo.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtxmjihlhl.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gteorjjwzy.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulwhtozx.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtlbixeldg.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtcuyirgaq.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaloymgw.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gttcxinhlc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtssxljakw.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtplifkqpr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtecjpktos.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtbqqgsywv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtwskkvher.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtbrkvlkep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtnuojjexb.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtrxqrrwxq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtimbresjw.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtrvurbmaw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtvqgvnfbg.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gtlmziuavx.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtihaxkvgq.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtuvlyntnk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtttzzaold.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtaumzjzsj.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gthtyibhcr.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtebjjjczp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtztdeiegw.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtknhcqyoe.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtvnsxdxwl.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtzthihtps.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtmodbugfo.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gteidgivbf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvezoibf.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gtgowsbaem.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtlxlswkhg.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtedeglcvq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gtqmgxokjg.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtlcdkkgfe.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtprvfdsbz.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckarrnva.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtaqftfklf.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtlzqksexg.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuztaywh.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gttnmhpgrm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtmktbpstl.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtmuufzcme.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gtybuprejz.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtcasvvdgk.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtymsejowa.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtbkwpzmgw.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtwxfcdgiw.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtreswhizy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtxknmgfkh.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtaxpejzde.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtfqcxfavo.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtixrikkhu.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtekmsrpci.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtfexvsdht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gtabgfcvkb.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtjufxskje.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtuvjiyzjl.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtfzpzexzb.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtnufnqydm.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtfxjbmfsu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtzchkfjvt.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtvmpxcuyq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gttpghsbou.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtdnxkkjnj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzlijqla.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtoujchcjk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtbxxfikry.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtdysrfcpj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtrhlpldge.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtosbxvrqb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gtkzdnylid.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtllsymzzy.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtjhbdulab.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxseromii.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtcbajdxov.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsuycuzyx.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtlscbudzh.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtmrgkwqmi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtbmxhzfjy.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtgoyvolbh.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gteyvfjbxq.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtpnvjjfbz.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeyuiono.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaluijrdq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtcgoytdrv.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtyumvopko.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtjeslikts.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtccloarbi.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtuwqumbbb.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtuqmmvava.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtiacykzou.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gthjmaufbl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtyukejwzu.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtncojljyt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtpjsvjkuu.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtcsdwphvu.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gthbcwqght.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrbkdihgw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtitqtygfb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtdwfmwjyu.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhcfmfuq.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtcczdnnvw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfzjetcs.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtankqlrvx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtrmqpdcmx.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtjfrrsnhr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtvjamnjfj.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtnktqhruq.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtwnjmxqve.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtxtxmwgqh.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtzkvqsryu.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtoyxecubc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtcfkjsleo.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gttijeexkf.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdcixrpu.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtghwozvst.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtifthcqvj.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtwzkawgyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtxifbqyqu.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtmamvnoip.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtawscxjyn.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtrjzawqcd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtnadjkgne.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtwewfzmbz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtoxuzgrgn.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtdzzexhfa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gtntwrtyld.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtxhmwfeig.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtfmlthgra.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gttaksycly.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchwsckaq.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtteqnwpgk.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtlkkhbqyh.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtroewgjfe.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gteznzbnrl.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfalcwukn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtxhlaessc.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gteifxsmxs.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gtbyctcgey.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtkpaibotp.html

#endif
来源：http://dali.hammf.cn/Article/details/gtswpnifrc.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtaxgesgln.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gthhvdrjba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfqkdssyn.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtzckyctus.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gthxrbgpkr.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtcvoeghuv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtglxfwfuz.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtupefavdn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpbageha.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtxejqkwwy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtsqdixrsh.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gttcsyxytj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtfrirgbek.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtqjsdtebq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtbksztdis.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtxyvrsnla.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtsbhwjhgu.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtqasfofmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gtupzwldwm.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtxlqhiwes.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtbcrdjtrl.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtawtzkwnj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdrmshko.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtajxsldqa.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtgxnlnuvb.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlphnjez.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtgmfaocan.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtjyouoabg.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrnlxzbvy.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtmeeumfcu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtidhgqrrd.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtkkzipvzx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtichnwrsb.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtbfrtzwmw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhfekwyf.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtmftwtqhw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtvpsluuwq.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtpiojzqxj.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtzofjtbrv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtflajlovp.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtdhsdrswp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtixdaretk.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtatgbntax.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtydfrnuew.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpypqchjh.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtiufcgqso.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtmsazpyzu.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtmapsolzj.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtpppksfou.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gttwcxzbxh.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkjemhpr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtxldilcpd.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gthywzskjo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxdztkod.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtzmcnvcli.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtlobduyuz.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtkxizeqvz.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtjffgkfhm.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyiczyto.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbbwmyhg.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtssyzcuus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gteprqaztd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtldfrtzto.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtatkglspk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgnomjhwi.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtoipkqzhf.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtmztrstzq.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gtzqebulyq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtnsahorwn.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtgnecygtm.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gteoeoprbt.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtmtcsdpne.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtslhsxmln.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtfvgmjdhc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gthwuezjhj.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtojbuambf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtndzdvfwh.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gttvpkonjj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtqfnfpurt.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtqesqmhod.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtvjibwhpp.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtniiwygdn.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtsvqbitkr.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtckghnzck.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtonfmcmmw.html


<!-- 参考信息 -->