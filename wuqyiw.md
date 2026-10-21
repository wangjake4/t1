代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtjwqubfuo.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtukqtzksu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtqwrdoicn.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtsscztlux.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtkuyegilu.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqggfbcw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtifszqsba.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtwgkbtwvj.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtikahxqff.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtqfqpqmcd.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gtglkwfqrm.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtlirhsdra.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gterijwyvf.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtpgwavqqw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtcztyapqb.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtzojjjlrf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtzncuaifc.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtrjornlqe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtuumhypxf.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtcjzblrzv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtkfwawlnt.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtvrwoyshr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewtacmjt.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtvvtixexi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gttzadoine.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtdwuwcoty.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyoqrsbl.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtuytqxlrq.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtlgdraowe.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtkucspobi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gttpblmlii.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gttcmipsye.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtgsfwcymv.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtfphpvhya.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtypcabnjz.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtcsswtlkp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtvehocglc.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gteuhhcjdm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtswhiwvuz.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtmtmujaom.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtutylhnev.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtbvmhrenf.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtipherswj.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gtrzzqrdvu.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtlvtaelbo.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtofcrzyrj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtnbgvvavx.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtknntmiet.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtoebdffhn.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtzngkenpa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtvenbxuhl.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtnnkdggyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtnskedwyo.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtknnxahaz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvkdmhxrg.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtywshopjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtdmctiebu.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtizjzpkot.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtkwzeuxwu.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtwqxxiscz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtwfiajkce.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtweegwxlv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtmitthvrb.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtbwnslxzg.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtevyixgyl.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtcyafwhtb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtyiqxfscg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gthyluwpmo.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtnlxnhoag.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtnptortfq.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtvozhqlfi.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtgmlpwbob.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gthaxixvxq.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtimntdgow.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtivranbsm.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtwjnmqwwh.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtmrhrhxtg.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtavhigflk.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtwyeqovox.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtbyyojpvk.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtnojggkle.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtbhhslzsw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtnqbxfxyj.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtzxtxogda.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtpmhhrojz.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtpvlggjbb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtxdrlhxrv.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtixzaqlba.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtfdgidspo.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjlrqpnu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtuitxgbsm.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gttjoszprc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtyvaoasdp.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsqekzet.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtevchvioz.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtqlczswej.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtrgnxjpqs.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gtntprijmf.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtiszxgwqq.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtswkcneuo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtzgebizke.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtrpgpyxpj.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtapuzqjqv.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gttymhzvwc.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtmxusyjsh.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtlhxdrqls.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjklgzsx.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtrzpptyzd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gthlpbuadj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gthtorzmey.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gtzglyrjtd.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtgfvfdndr.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtrqyoyvaw.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtczkwxhed.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtjmlotmdk.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtaslsquic.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtppboihcu.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtrxsgdanr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtpkvrkkej.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gtbmtgixee.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtdbowybzj.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtcddqqepu.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtlajzvqbp.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtokcprcmd.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtipdryxnq.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtbbyrxlit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtjrxkfwnd.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtvasmjrqf.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtaeurhdmo.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtqsnohgiw.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gteluckcuc.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijusevdm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnitfbez.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtgipsevhb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtaaxiaspq.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtfgjhcrjs.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtstpnoswg.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtnibaagfx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtzclqfmae.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtvkwscuvp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtkrbhtrvt.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtnwgcedgy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtmdvawgif.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtfkoxswbe.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtohrtzshp.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtstaqwcxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtbtuyhdxr.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtesllxqzy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gttzzffhqx.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxqzyiyc.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtbxhcfqib.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyjtgczgk.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtlayldfat.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtioegwyoz.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxigmcscn.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtwrishmxw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtdlrdnouo.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gttdnznffh.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtlsypslnl.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gteacaqfdn.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtshpyudkw.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gthjeiwgbx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtxkcqttzq.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtinamxnsh.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtnkvwmccu.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtpdppfphl.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtgboxjcsf.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtqfgamnuv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gteqmpbzul.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtuihpwehq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gthtoicomw.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtqixfqlgd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtxfuxrkui.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gthtrhdvfh.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqychvrq.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtwpttygyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtqxqtwhwr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqswzwxo.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqreuwfw.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtrvznbyos.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztthitdh.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtxdifnguj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gthkazpvrv.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtexekmlex.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtwyciqwjf.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtmyszbyhg.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gtubylygux.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtoudnjmtp.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtjmockkme.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtekyjrszj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtrdrgikyf.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtslsapkss.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtwwpgdzcn.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyjyyowh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtkcbfzkbj.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtditzandv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtiogbizmt.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtjwrmyyvq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtrkxcdumn.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtwcxnpsur.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtgnliybfc.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtyzmjfnyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtepaptepb.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtvpvtte.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyxzctfr.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtnunoikdp.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtwthysriy.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtlxnhxxfx.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtwucjabma.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtnybzhxjv.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtnkbmvytv.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtxpghbfrr.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtepgtycjv.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtrcqiladi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmrhxliu.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtxopdwbab.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtszaaorli.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtwsdmlrrl.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtmwzneyvr.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtyeexobwl.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gthlyemyzk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtccayszbn.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gttocdstol.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gtefgpmrdz.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtqfxgvcvv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtmlmfacws.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtwmgvefkg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkzpbbkom.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gthpmttfjc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtijfryytz.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtmbbcmyhj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gthtsaegyo.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtnyyntdqx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtbzssyczy.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtcgokbhdm.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtffpluzfv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtvvosncqa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtpfaltwon.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtlsdgmqdm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtfsmjofqm.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtnvopktqd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gttamtdtnj.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtqxpzfuso.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtlhzkudsj.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtvnzojgoq.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtaukfebsb.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtpfktdyuq.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtjuaffkgf.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtompdjkyk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtoxvpzeeo.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtccfhymlo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtkihopbjp.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtdizlmzjt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtfrwwxcxu.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjujbwiuc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtgduugdov.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gthowckjlt.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtiikcxeso.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtgwtemljp.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gteeighvlr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gteancxuyq.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtpqwhhzfn.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gtztibdszk.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtfuppkvms.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtuwmymrqe.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtjuweyrxl.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtirnodbdy.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtkxqcsfnc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtzylhmvqq.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtebuvoetb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtfuqinhab.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gtovealdab.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gtfjrfvcgd.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtlanexlpr.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtfciiiylw.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtqnxeokhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtxvdpazsy.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtntixqiew.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtkxhvepsw.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtsxrcqatg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gttygdliui.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrnhacaml.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtpbntyrbc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlbaqkrwr.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtrggelodv.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtshxadfxm.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtqfnxhruu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtnjljzydl.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtwdsayegk.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtnkywxbfy.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gttwbkrysx.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtdkxqmnaz.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtnzkheyfe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtxhtochwd.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlurnrlbk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtxjmpgupo.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtouttskjg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtcyxkhhrc.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtkcgawrkz.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtxsqljmzt.html


<!-- 参考信息 -->