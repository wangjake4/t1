代发 wailian999

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtbzjalicl.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtdgkskucn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtxlrxylbq.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtxtxhbaod.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtytwxwfls.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtjlyatdjq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtdnnkhwse.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtrmswrwjz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtpjexlqir.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gthgcupsci.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gttfwvqnts.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtxbpnhozz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtjcttkait.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtfmnemnuf.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtwapoiheh.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gteuyupiav.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gtnnmnhqlo.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtpsgmwmmx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtglyrvhle.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtscnzdtgj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gterjbnubm.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtiuwlpcmb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtqhebpewt.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtliyfgsfl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmlisbcjv.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtetjyffrx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtkwhvshts.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtrmpzxmsh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtztrkghtz.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtqtddxnxt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtvgozpdfx.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtjirmxpcf.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtamqfjksl.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gthfokyyjx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtmosudgzw.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtjkyhncxw.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gtktnejxfj.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtixgkjukb.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtnfrilsfp.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gthnystgwg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflwswjjn.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtjtxlrlku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtcaxjngjn.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxscftmrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtlzrgnetn.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtcpwanmmf.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtxzqnhvvy.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtzpxyyksp.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtvzgltddr.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtdpkzysub.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtdmyqjdjj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtekuozwym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtzyhupofg.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtvskgoace.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtpzliezff.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtktmycnog.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtejqehlzn.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtcvtfroob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtohcjwcsg.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtxenpekjb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtmneapvlj.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtnfoteear.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtopuctssn.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtrijntdhe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtzqznhysc.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gtcxpmbglm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtmyguqcsd.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtmcvpqkli.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtogrrrnyf.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtflhbpznm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtfnpnmdwt.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gtbkckicky.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwiviuar.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtlpmgggvv.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtflkozfyj.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtccybjmdb.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtwoepugen.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtrpgyqjni.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gthujqdbiz.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtjrrpfnzs.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtkytyiuqt.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtqqdmbekh.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtcwlsvzmi.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbwgisff.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gticnjzvka.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gttcqvjakt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gtdpvnlfdl.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtbffdpnqw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtpfvzysfr.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gthdnlslny.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gthaxmhush.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtsvvgajgq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gteusquxty.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtbziohazz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtynbeqzup.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtkyokexui.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtgbrwhpcp.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtemzrgrzb.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtjtkjgcdh.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtbxcyojob.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtmswfzdrd.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gtrzflnzyv.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtdaiocvmt.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtixqslaif.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gttxayygii.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtniumwhau.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtudmtmvbm.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtdqcjwing.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtjqcwoiwm.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gtolohefai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gthhwtzyrf.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtrmvxvugi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtxegtmhbe.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtpicsvenz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtmwetefyn.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtczfqhkfs.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtzrxratip.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtbdkglyfr.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtpehaqzxo.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtbmezxkmw.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gthjqwxchn.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtdtksfkax.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtlwnqjboh.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtaxcrxgls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtdvcxexkb.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtciradngf.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtpioyzjpv.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtntdcsabt.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtnomquzmq.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtdtjjeewb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtqhwkzvxl.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtgcgrhaur.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtkxfdkwbs.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtbuptlajn.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtwosnmipv.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtzbqeyvtq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqenwmaka.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtialhipzr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtfnxkvidh.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtkcjnncxl.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtmphkaqtr.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtconvjmof.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtukdtipcq.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtaarqdfkc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtftcnmmio.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxktdhikb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gthyhvynjn.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxadbwod.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtwrhjxrwr.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtbynlipul.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gttfexpxvu.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtmdigwsiz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtjobthyih.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtlpnjptqo.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtbzzkglkj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwhnmmzkb.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtlrrssarf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkbytfhnf.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtiuanihfm.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtrmrqnqrx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtoxuwrayq.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtxjgpektu.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtvhoibvna.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtlyukiccx.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtmwkajvua.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtdsalisga.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtsxdvgztv.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtslpiljbd.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtgoktkhhl.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtovhdfcrr.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtnawahjzo.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtfbcusbod.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtxlwhmtfh.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtcfbxesgr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtyknvvfcd.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtduuneggs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwalweuoo.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtzacnktgb.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtkvsgpfur.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtgvzfgxcw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtvrcgfcvs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtfxgnreca.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtmaejzwmu.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtojcrtoyx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtxokrrbeq.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtfxvrnoxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsokbksbe.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtaatrbzak.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtnbszefzx.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtmsmpqopr.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtgtgpubxq.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtnpygrqhu.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtuqswpfox.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtinnspzpp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtripsotty.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtugmunuvq.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtfmidlriz.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtwypbjegl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtlntbowoa.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtdbqedrvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtpovfqnpf.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtoikxbzrk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtruorhgvh.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtahcfbghz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtfzhmpoiz.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gthljloiwf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtfcohkfuq.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gttaqyudbq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtbdoxpbnm.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtsyjmmtoi.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtdgsjxdux.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtuzqpxgsp.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtlyjxsuex.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gthvmsiwpe.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtuwwhmchq.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtehhtmwix.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtrnmieiry.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtabakajmo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtvsozekok.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtosgwkhrd.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtjsjxvrag.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtzgcxucey.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtvsoexslz.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtgpxhdwxf.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtvhzoduah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtejkujrov.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtbnrtadld.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtylicnegj.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtscnlinrb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtxjcrgqdf.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtfdiupnfo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtjnrwwawr.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gtkoradnjx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtwuoykfio.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtoopssxwx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtfmapogrs.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtfbiiacai.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtxjvcbmtk.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtgculjpsk.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtztgzrdlf.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtuoyrhidt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gttfoztlvo.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtqdwugakk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtbsvpjgrc.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtdjjxgign.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtmfqihcif.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtfmtsmhkd.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gtjgikknpx.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgciectb.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtrahrxohk.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtkwgjxfaz.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtxmoxboeb.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtpsojhips.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtkawvdyvp.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtufzmwila.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtlddfyueh.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtlydkbcmf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtxacnqygy.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtskttfpbk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtghrgcwvd.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiuwpdgm.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gtxocnzrxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtuvrpitzr.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtfysdwrmk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gtyyiruzfg.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtmqujfkbe.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtkyongsck.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtkfwhmmhb.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtxuwslryf.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtvhcxkmfc.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtfrxnbscu.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtqrnjgxgp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtxpebavdc.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtzcqyfvhc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtjxcceuoc.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtidzjqubn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtpzknzlxh.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtpwntkvev.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtjjexiuat.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtstjaixno.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtkaoxjxzn.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtoahyljoe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtqtxdcrpt.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqqvjvrb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtcdoenpug.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtblgaljto.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtdftmyike.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtejeumqux.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtowmkrfgb.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtrvebndam.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtgscthlqa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtuscgkiig.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtuhoyzhzu.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtzcdesvbg.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtxuoyupux.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtozdaqonk.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtbzfpodqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gteseecjrf.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrpjutgf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtlxcguvcc.html


<!-- 参考信息 -->