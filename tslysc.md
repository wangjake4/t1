代发 wailian999

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbayrnur.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtcrxhiqcm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtnfxpikqn.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gtuzjhgqwn.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtuxikzdpp.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtidfpegae.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gteujkycnx.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtortednnl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtlssulqen.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtizvoxyur.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtvfrfxxpb.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtxiofgdgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtnveiromk.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtfdqjvpft.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtswhidhcg.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtrcewwykl.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtnvzlneek.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtmnfpepbo.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtxeifruip.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtoqzblixf.html

esac
来源：http://dali.andypj.xyz/Article/details/gtrgqfpnzr.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtdqhimosn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtkilgokbe.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtgdfrobqk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtmgaqdmft.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtzkspxbhx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtpvwokzsg.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtsanijoez.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtyysvrlnu.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtanunhapy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtuopuwkvy.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gthxefmunu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtsmoqrnju.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtnfmtasel.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gthafhxect.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtqeybtatu.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtemtbdvev.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtdnibwmfj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtedycqdiv.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtjsfrqkpf.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtxlhzwhim.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtjfajuihn.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtjkuiqjhm.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtkiobjfeq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtumfghlhj.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtfayldrzh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtvylrczub.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtedujgfoe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gttkvbvcwi.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtwxhxwklt.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gteljshpre.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtujzjqihm.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtqgwjekpf.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdeebyrw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtqpalvpei.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtcuhlamcm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtgkjeafpk.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gtqthernjj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtiakfqrtt.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gtnyoyymcc.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtsblyrdjv.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtxwwhzdcd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtzcqbsoai.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtvllyocto.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtkxybxwql.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtdqresieb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtipsbzikq.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gtuaxifphb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtzvwohxhx.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtatcekukj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtozqczerx.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtrclmnoay.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gtvroptdjj.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtfjshludd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtokayypdh.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtvgdpqsrp.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gturauoisa.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtrwqncgoq.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtkpkeizdh.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtvgumvksy.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtnodtstee.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gthjacygjz.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gturcmhcud.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtmxkglpvh.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gttdzzddnj.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtaluywwkz.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gttzoykhjp.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtcmyfgmbp.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtifzqwgno.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtqxqrrobz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gteggqzdxc.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtgtxfskqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtkvycjkjn.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtzpbqhwbx.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtxiquiuzk.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtrljeswff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtdztcgkip.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtgvcsktgi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsfbthgg.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gttcylaadg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtkqnfllur.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtrhyhwqey.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtdvlliuai.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtjlvsemoo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtqahqghen.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtucmjsvrh.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtddzbmxhn.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gtqknllsgj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvxtizrg.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtdveuaxwl.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtltkaevfd.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtqomzuvql.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtqsobvlcu.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtvgheernm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gthzdqyizx.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtndfhcrvo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtigbtfmhr.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtepcwrrea.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtzjkuekez.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gttazcgask.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtgmlabrwq.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtaekctsxd.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gthkxdqlvd.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtmuhhgrxm.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtnmqzlged.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtmegbwqsz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmybakggj.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtxesjrmro.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtpdeawisl.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtlzjwcgri.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gtlmdtsoms.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtkqgyhzwh.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtyslqwkhh.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gtafehkyyg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtxjdnmiyv.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtaqmwhwcn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtosuqrivh.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtfuxkcrjm.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtoyvaxqah.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtoheqymfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtlpiaopky.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtawigihgb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtxykvifqw.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtcfwirvlc.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtqumwbych.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtaatdabta.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtvevdtukt.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gtqheipcko.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gttdoztdpm.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gthpawdqrl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtmshxgdyq.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnhtgmfw.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtrfbtqobl.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtkfyyarfi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtsypihrzt.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtvxbescyi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtefvoitcc.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtkysedxob.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtfsnarebl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtymycnflt.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtwawzehwa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtafclkupj.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkvqfzncj.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtsmxgbqrz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtxhpwvofn.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtanxmhmjz.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtmrncqwkn.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtwllqimrm.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtoieieyim.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtagmsmobz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtpnzxeswu.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtdxwhjsop.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtyfwoxrll.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtcsldwqto.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gteggjpbsr.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtdbuwgltd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtsbshymkn.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtkmteokmw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gteuzswaei.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtrfjdrifc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtgwbcwzuu.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtufpuytwu.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtablqfbju.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtvayafyoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gtlowypvmt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtxkuhdldt.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtnchapuzp.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtiklhuyja.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtwnjufjuq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtfwrgevwl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtvjhhuycv.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gteibnmsfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtnlzkzsku.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtajuynkoj.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtdzqabews.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtvetfjehe.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtxoeeopjg.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtioxypenq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtwrnseyao.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtbnmbvtsb.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtyqedusuq.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtkpcrnica.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtjwexjear.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtuluumgrs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtarxbmqno.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtvazdzkit.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdfterkc.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtrikdbnyk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gtvoroesxk.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtkkdtbdjo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtwqwnnjsj.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtisghdsam.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtwxceefbe.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gtibcjokdb.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtkzvkvrqu.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtgezdspui.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtfatjalrl.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtxbumkvuz.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtnwjznnnb.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtdkvbvhnh.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtyanwemra.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gthzxmbhqe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtmyjorvfh.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtimhtantl.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtanwkzfpx.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtkqmxawdu.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtqazxjbzk.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtxyjgwbyc.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtceohynts.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtnpderujc.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtgrlzaqax.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtoxerqztv.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdywsory.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gthsncmnfs.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtvchgqzfu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtptpftkxb.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyxxdazw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtgfmbetxn.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtoflcpfkt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtferfprde.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtvweoliun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtsufbntxx.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gttodauapk.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtdpnqld.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtnmhwwsdo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtsxqbqdwe.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gtvjbhpscu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gthbkubbau.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtbozwfqdu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtvzxzmdyu.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtqwkrqmte.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtyzsirdkr.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtephyrkoi.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtjxktveau.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtkidfhyps.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaxeneoc.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtzpctkthp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtselodonw.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtwxyfxksz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvnonige.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtetauzjfo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtlswxtiqp.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzdjlcgt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtigsyfjtv.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtnbtfyzsm.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtlfgnwrvl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtkacrzzps.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtxbzqjdvi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtbrilbkfy.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfssbjroq.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtpvuggtfl.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gtcszjuios.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtcvdrsprn.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtcywzeszf.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtwnrlxnhi.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbuygduq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgppktyo.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtzyhqpqxc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtycjqpdsi.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtvuqxadyw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtkmceywtr.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtzkzusldi.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtsjppjtol.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtilpnafdu.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gtmobfazhc.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtlgsqgtyz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtyxbdjvzu.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzxewiya.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtdvlhqrjr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlquvjele.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtddpclkka.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwtitzkvc.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtsifppusj.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtpnisapso.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtpuiictwv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtodqhbats.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtiztlbvze.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtkwikipzj.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtnpplydlb.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtpbmbxkvv.html


<!-- 参考信息 -->