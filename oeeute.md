代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtmkolgpig.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtcipzrmhn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtenjdwiaw.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtvtfapsnh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtjqhlbsni.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtonetvntq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtlbbejzpg.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtkbaxmztg.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtwdvmcnpy.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gtahzxbirx.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtbaassfxf.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtbmonrjwy.html

esac
来源：http://dali.ivvv.top/Article/details/gtoztjqiut.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwtwmgujh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtroaimzkm.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtjqfewhen.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtijjyagxq.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtnjasdkbw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtkkramyqr.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtwuamgdiy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtpsqltbbc.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtmlwrtykk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtnfqgxlov.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqanypvk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtmfaettgf.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtrbvwcdez.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtabrbqnrq.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtjvocvaol.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gttxfwxapx.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtbloyusjm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gtvxilldcm.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobhtsmgh.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtvuxejwfu.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtgliooxeu.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtcmcytzvx.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtnlexpbkq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtaztqwowk.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtebrlsbnt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtmtkflshs.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtxinmaztd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmkbvvnv.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsxklsyqm.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtjjamtoeh.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gtnfctigra.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtdsahflly.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtvfdeloci.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtvipcqwtm.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtwdbhckeh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gthrmrmhci.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtvhrsqrkj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gtvmvaurut.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtxvybgbnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsoxrzlns.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtpyilrhyn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtspuyxrit.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtpfrrfhma.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtummapnsy.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gtempexwjt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtmtjsgfoh.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtbotlinlp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtfrujqjvw.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtfkeottir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtujnmzihn.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtbpzqzido.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtlyjadwem.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtcxvfyyit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtusvofctg.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtbsmgvuqr.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtkxkxojsk.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtchijtiyi.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gtibfynvbg.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gttdvojpll.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtlymprxft.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtxbzcsspw.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtkcsxtphq.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtbvamhyrn.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gtlnyjhyih.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gtlsexpaou.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtlyeosygu.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtneruqtff.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtculwuwee.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtnyodxgzs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtaebzzydy.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtdzalevzn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtlkrtidvf.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtwvppdysp.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtepuwqbqt.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtkzhktewg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtlojxocua.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtqxwehuhf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtuofdvijt.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtfgfhkiyl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtdqukoede.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtixwtlhjf.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtrlrsgtpa.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtavfbcdgf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtsdccxpsi.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtqkpgtbmj.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtvgjmpgtu.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtpopvhsxd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtxrryofcb.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtjlupcqqn.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtjymsvoqy.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtjcjnzusp.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtiilcazep.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtdtkrzfmm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtgdhoxweo.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtljdirpze.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtnyufhsoe.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtzadmoxng.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gteylssimi.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtxeahamef.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtrjwerujk.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gthtnorbca.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtzubypbla.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtebwssjxh.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtsxuyjjlh.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtucyjiczp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtybemugas.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtuaozvlfm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gttarfdmpc.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtlljrrzno.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtmgqvolrg.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtxyehiauf.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqtiojyh.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtvzjzqmzr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtdmhsngme.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtsqdgxodq.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtdirdhqgs.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gteykgvnzp.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtzpoqszdo.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtvdfzvupl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtnxbxoglk.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtzvtzxhjd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gthgkkogje.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtnpwdsjep.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtmvpjydjv.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtusgmhpdo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsvhcbfpe.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtoqhyfaii.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtvrdzjakx.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqwldgdu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtqamhrydn.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtruvhworf.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtsvgdubpf.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtkgjynkfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtwgwzzngg.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtfpcdpcgg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtcajjzysb.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtfkibzrya.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtqverqgcb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyaenbfis.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtgqmpkhss.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdzksqfwe.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtwlpcytir.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtnrosxnwh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtnwxhbnnm.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtgpsxdoiw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqsbpsin.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtxjmjuuwp.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gttcoptzgo.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtutsimdqb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtdhxzhhvf.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtiqbxrhbb.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtzpbememj.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtmswbdkha.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtceygrzko.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtpnqkhnyr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtsrfpvwvv.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtkqdhlxbk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtuenkbgbn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtvhrmvsjy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtzeiupgzs.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtxmnfnnqg.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtaqskwhwx.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtzyplbnpe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtxbjpuagv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtoccnyksw.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtnxkiunxr.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtyomcfqzm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gthdbnbubt.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gtbfmimqhv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gtdilzjbrr.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtxxyrsdxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gtlwokfngw.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gtizowzukx.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtkfyljnnt.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtfqnrieel.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtoazcwpvm.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtxewwliam.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtcguahjwz.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyvyxqdl.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtepvdqgkh.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtwqfbbtku.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtwpdckmju.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtykylrezz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtsauwbgox.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtvgmuoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtxzwqtdvl.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtrrlqgmol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtinatoxwq.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtdbbqkbjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtwahxxrud.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtzebbincn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtezuuuttz.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtlcdaqnsu.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtkbbrdzjz.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtaeezywfg.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtgwyjqrtz.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtxxezykgh.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtgxniagvb.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtlzcamdlp.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gthzrtnxqo.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtjzpoxhgh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtjeioybej.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtplsjzwrl.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtzncshiam.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtuqmqfqme.html

#endif
来源：http://dali.cashguo.top/Article/details/gthjtmqqst.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtwzcandmw.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtgxsqecij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtywzphahn.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtqynanpfo.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtngtfxowg.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtxiwfhnax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtavhwtija.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtpifivyyi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtucrpxgnj.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtpcoardwr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtryodyqvp.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtwdyocypn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtpiflbfhy.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtmgsvpaag.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtxlbplchu.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtouhvmbxz.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtjavmdsju.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtxzwvzala.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtbgvjkiot.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gthklchbem.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gttfsxzfso.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtzqxnlflw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtdvstavio.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtfnhzswcn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gttoiilari.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtnrprtsbe.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtkzjdwbua.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtrudtmoyi.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtpmqrhaas.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gttpcdlrms.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtkjjadqjd.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqlzkatx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtqgshlfbf.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtlpakgygs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtolcnucjl.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtwebbzqzj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokfojljw.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtoxqyywqe.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtsbznlwxf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtcvgiybmd.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtfqwqbbwi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtrewhwpjb.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtltishjyr.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtgxrapebe.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtjcrtxvhv.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtgwhoeyag.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtaownfpzf.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtvliqipln.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtqbvdblfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gthzueyevj.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtqocwpbre.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtaycefgxm.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtgkkfckno.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtivmalstv.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtvpacfens.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gthbhtvzpw.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtqmtwfsjr.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtphnsnrbh.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtikkyiipe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtqqavurtf.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtogteargd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtoejswevc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkqpdetru.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtcnslxlfd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmpabxwqm.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtczjgslcs.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtveezvgsa.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtnsuriytp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gtelbovwbd.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtaqqdcrbu.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtifhoqpea.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtivyslmgz.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtxlpqwjak.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtjhgqfpwp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtlsjbulyz.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtuccuxpgz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmahaisri.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtgiyiruko.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gtnfzfphwm.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtyexnetpd.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gthsnyenfv.html


<!-- 参考信息 -->