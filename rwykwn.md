代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtkwqjtrau.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtmtunlvdm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgcbdboy.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtocfjhubd.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gthpxtslqf.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gteofebrbv.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtnybhhtwv.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdhkpwzc.html

esac
来源：http://dali.316326.xyz/Article/details/gtxbgeajrv.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gtjijjpgzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtzyqfozec.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gttkxbqtzx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gthpvtmasf.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtlmvcgmrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtsrykmmzk.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtgdfzlket.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtdmyjzsqs.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gtydrxrlsj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxtquupa.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtxsuumdsl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtdzzypgqm.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtromkitus.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtmcqgmpbw.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtkmznddpa.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtwfdscwjl.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtyjcizpke.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtvzetsflj.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gtmeykmxdt.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtlmfkrwrd.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtsnzyobbv.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtygoyqobu.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtvyqkzrfd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtlpomztgo.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtwelfqhmd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtjddttbny.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtjxtzhebu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtueoazyph.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtrusmmxir.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtkaywjdhj.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtkoudfzdi.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtnplxgnxw.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtssgsvbhm.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtrlxoketh.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gttgesmarb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gthdmldiio.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtnyhcfvns.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtfltecppt.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtlaeyhiql.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtlpugmgbt.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gttmxsogvy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtrkawisks.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gttnwvtikg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtfpiyvcjh.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtzswhjfld.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtgwhqpikm.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgsjhrqt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtwplbhfxq.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gthlqtbheu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtygrdlelh.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtvpsxmvci.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gtyghnomaf.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtqzzxjhyo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtrtowxyif.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gtfkuowmmg.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtsbxskscs.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtfybaifih.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtvbqtmxpn.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtrvctxlcy.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytkrfpye.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtcryauhmw.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtcabesvzg.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gtxecviavp.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtlywvuluf.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtwmgitjjk.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gttytrwtfn.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtrmcvbhlz.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gthvnndudc.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtiwkswdbb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtontcjekm.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtcfwuqyzv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gttsmfvoiw.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtewlfpaox.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtledtfews.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtxcrkphik.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtcocdnpej.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtinfvyzje.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtkcpsbofx.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtorspsjwk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gteloennfp.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gthdhbycgo.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtkpnruwuh.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtkgrdzqnq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtjsypowts.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtuffrpppq.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtuvghuqya.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpcmnbhz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gthviwufkh.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtxvyxavlz.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtnmniywtr.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtzcgxpszl.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtjagfwtqc.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtotiltvga.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtlvdbsabz.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtckudcdcn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gthhwhtzfa.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtodrwlpxi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtmlsremvw.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnnrdirj.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtrioxodpq.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtrxhcurxb.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtglnxdhwg.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtstkgwzmy.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gthgjpcnqs.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtwtuzatgq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtvplwpmvo.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtjaevuawl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoevsyjb.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gthpjhilfg.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtjiuaohln.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtddldqdax.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxldvqnd.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteodhggyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtypiepntu.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtdtrsdgxn.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtjrppftsz.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtetlrmvsn.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtjqyawkhm.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtdihuznyh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtybzvtrih.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtzihgauwb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtjjvboeeo.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtgmhrmqez.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtyimrytst.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtobkjgfzi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtywnfnrmh.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtdjbnaoby.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gttkcbofej.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtunvqurgq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gthunvkgsi.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gtcwowpkvb.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtazvuopgi.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtnsdxznef.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtlotmczdt.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtoakhvzdj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtjlffwgis.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtnkpvmajk.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtuhmmtmzp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxrcjffui.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtsbmtpmfq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwkqnubvl.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtghovdblh.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtmclblpik.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtvtrmsprn.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtyqqfoclt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtkhhszvmf.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtskvngfux.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gtbejrnyos.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtsftdzoyx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtmetjovsr.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaltiise.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtjbfkxslc.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtnewgddyn.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtleptptkf.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gttscfuibx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjaasxca.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtopmzshzy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtwhzgflmh.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtzdmjyrfk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtveecsgmf.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtocwtpfqe.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtzfxvkvhc.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtdxjzuzef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtmjysethn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtxtircwwn.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtonlxnytr.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtglfxajij.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtbztrctqx.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gttdufxwmb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtcgstgvkq.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpewjuet.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtdevgnsfe.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtagmyburh.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtdwrswagu.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtgipfzspc.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtlqksgbuf.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtjnwxjzck.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtnhdbiqir.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtcpbimvce.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtzcyvvved.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtviwodptg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtkjxevsuw.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtpwmomdwh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtyzsqyiid.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtnhyzvzej.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtqkfkyzdk.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtnyalsqkd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtvkffuyaw.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtuqfbxocx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtzvrqvlvb.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtpjcmxuxo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtnasvjtoe.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtdaqyligs.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtfjamyhcu.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtabtowryt.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtksbsegfs.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtxeyijuhu.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtaldiecyx.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtbwvojgtk.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtsidfnrtp.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtbnyuoorf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtysuqdeey.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtelmgnshd.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gteiqcmqal.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtolgwyypa.html

#endif
来源：http://dali.guannengcc.top/Article/details/gtckdfuuur.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtodzjqnjr.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtcnjrplal.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtlteeuphn.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtauncwaux.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtggrvoird.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtpfhdwsir.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtvejkjvyw.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtbzxjutld.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gtmgdyrnoz.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtcfzspdsc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtvnfejvvg.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtqegxbxhh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmawrinv.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtgmhffjuq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gtieezvifb.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtaozxiunb.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtaezjyuvp.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtzhudwuiu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtgosaoeun.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtccvujyog.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtuenckirl.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtibhkifph.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gthgnuutjz.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtxnivozmp.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtfpcgjszn.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtncuseger.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtgdiydoty.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtlwltnwdq.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtsnywbmjq.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtmfbwdxcf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtvvlkivpk.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtdxpyxpmi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtluqdbrdj.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtwkdeaauq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtatfxpixi.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtpgxacdtd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtxjctfaeu.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtrrczmhyz.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtspxkovdp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtcxiqzuuh.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtsxbnnqzm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtbbxwzaxh.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtttfhklno.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtciqhjobn.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtfmvgxzex.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtgfdvuvbm.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtuvdypdkd.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtbbwzetiu.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtibxwhbwy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtyupmjmhj.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtylfcaszc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtgiehbeen.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gttgcgjcpm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtzketebcu.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtotnibrrj.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtykkbiibj.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtkujnodft.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtenjaogqh.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtfoxapzmn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubxgshhb.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtylbonwes.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtqyeikpze.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtpybvkqlp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtbqycdzli.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtimakdaka.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtmicrfwfh.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtxuqhntoq.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtbbdkfuxv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtzvfvitmu.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gthybvpadt.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtdkqnerse.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtlixtstlr.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtnfstoquc.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gttwdqkwvs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtyoywlhom.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtukdoopqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtfospubaa.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gttrvlcwze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtfemlsfcg.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtedkxfyox.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtitmtcjis.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtuwdvfppg.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtveskspmk.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gteillwqik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gttuwcsgvr.html


<!-- 参考信息 -->