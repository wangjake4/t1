代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtfcoeyozp.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtqdoqazgz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtwlarbqia.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtrixknzzi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtdulhizkg.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtjywmnhtd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gteviyybnm.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gtsgdxiqlv.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtyfzbcsyb.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtjsxklsxa.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtddyqqhqx.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtpkkvupen.html

esac
来源：http://dali.yvedp.cn/Article/details/gthtfxluhl.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtuhefaruk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtgcospdcz.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gttoordjcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gthgkspkru.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtbntrcbno.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtdwijxuoz.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtpmhgobpu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpluysscj.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtfqnbfbxc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtnptugang.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gtaduonukn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtvjcbfykl.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtbivxnhkb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtaamxibph.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtagxqylys.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtlbnrxpdi.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtvujpllle.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwfygqcg.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtklzpjqlg.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlnelxlq.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtlshioooh.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvksdbljc.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtowyezkof.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gtjkgswwab.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtthirzzof.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtcioraoet.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtebexouol.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gteuflxkxq.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtdojeqtha.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtcbznunpv.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtwlnnfywp.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtguypfzug.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtpkbikxbi.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gtmbblrvzs.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtcfzaltzg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtiupinpky.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gtfdtdnnjb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaxxhpuy.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtjbqryqkc.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtsgkcqlsp.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtdkkrkswm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtqikjcnfg.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtbrjdvphv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gtgywmbjah.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gturyzxxtl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtlmqzdqkw.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtbuvpoxhq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gtbfipgglw.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtrczeecfd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtfnazniqx.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtmhcbioim.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhvfnogg.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gthazhyfwg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtztjxeazi.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtagsndhab.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtczgyexep.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gtnqpsaamj.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtdaqomntg.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtusvvoaov.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtiggcqdig.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtlygixlfl.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjbppwoo.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtwhxwmtyd.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtesuaxkrx.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtwygijhni.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtbktvlfrq.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtfgjnkcak.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtcuvrmxoo.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtkhauncdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtpbhzzuka.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtlbsntpze.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtytljwqek.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtdgnqkxdp.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtyjibdlyx.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtaivcztqe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtpmneezak.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtjbrioldt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtoavbjlte.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtacamoyjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbfrbfqg.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gthekbzjon.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtlkiwbwly.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtaiwfplzd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtjmbxuhin.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtcscqzumg.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtopslbstq.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtktllkmvq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtmxxutxyd.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtajwwjekz.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtpeogaixw.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtbznclljl.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtrparmpse.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtsxjvjoad.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gttovmwlft.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gteehvmnbw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtoxnxgqie.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtkgwszlss.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtioglprbz.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtytaqptkc.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtzlgivthb.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtlnosfyqb.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtpsyqejmo.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gtmjufyruf.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtyixxifew.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtrjvfrvvr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtzvzdpduc.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtvawjmjet.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtpyngooae.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gttoryqdwf.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtfaytwgkc.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gtrzjmypgv.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtscpuotkn.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtwedfvhhg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtilvvowqk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtinmljsrn.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtffmexesj.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtbxoehtes.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtfobrroyf.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtuzmeacki.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gtjfozxuqw.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtiibbqtmx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtkbgictzy.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gthohwqxwz.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtpqzexbvb.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtrwnndfji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtgtipemsj.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gthesgaptm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gttfytjoiv.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtuwcjxhtc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtdlpnuwyp.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtpojrbdde.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtcwostvja.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtururcohz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtkqguimpi.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtasmlhnmu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gteqtmxofs.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtgfilyaha.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtgfomxgkd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtipmkcely.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gtuxbxrzyd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttuonadwv.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtrkmxbeub.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gthwfguldu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtycsfxjam.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtcsivqvzx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtdrpupcst.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gthatcizdj.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtktmreoiu.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtmdouuwns.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtzlzrmlmc.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtgiqqrbnv.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtfvwznxui.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtctdoqfne.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtxlsvqbbk.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtssnrptss.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtpvicxkmf.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtjuxeudwi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtmszwmffb.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwtsejzf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtzjnceiyz.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtsrdjqzld.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtzcairvke.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoghjucd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtreunfyuf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtjraynpdi.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtpujjsygu.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtrbyoxvou.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtnfbfuhhf.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzafoyvia.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtggjnuqjd.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gttktjgnbj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtsxklfyja.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtbriwwisg.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtittgjvxq.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtsguyrwxp.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtwcpyxnnk.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtprkvsbiq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtyjsmjpeh.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtacmliwwt.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtvscipsqw.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtyrjrxlgz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gteidajmeb.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtvuirmpwm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtqoqwrktp.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtiltplxpr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gttjfczbyx.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtnhiqksqw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtsnligsjp.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtfmoxabsf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtodcarrfm.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gthpftttzd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtkyzxfetl.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtkhwdwqmo.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtpkbpimvc.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtydpeudme.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtomzxfmrp.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtftrxqidj.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtfftpmiay.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtpaxhwvri.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtmuwmgybf.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtwscirskc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtqrkqhhxl.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtozquurbb.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcqmnjyd.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtylfztysu.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtfftsioiu.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtrrciqmyr.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtnewxlbex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtxsottqkg.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtjriwanjj.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtbotvcmlm.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtpiqfuygs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtbrdmlgot.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtcokplcea.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtunnuplpr.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdgqowpe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtadawdymp.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtkgzkctux.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gttcqhhkrc.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtaejgzasz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtpyahajsp.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtvvqmhmka.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtrjhyqism.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtkgyafghh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtagttgeyp.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtitvewkci.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtvyucsbhq.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhilhdeo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtggnluwxp.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtnugryrui.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtowqguxhn.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gttelufmls.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtzjkjhsgq.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtvkjyvbdx.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmrsbsjua.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtttqvzxjp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtfgwymfna.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtzhpxglqq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtlgqsilnn.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gttcdbjurk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtuwniaxzv.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtybyvpiyc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtjxyvtbwf.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtdnlrktoc.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gthcdjulqt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtwfjuyiun.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gtwohafxcj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtbaotxeyy.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtkwssaiur.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtgofgjnml.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtgojtolzy.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtwdqqhabi.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtqfgovwht.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtfmdnlyzm.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtvgrorszn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtousctfol.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gteysetxie.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gthpsxxwai.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtexkvrsbh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkswffmlp.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtnpmovahz.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnmwxgbi.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gthactuiad.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtemtvkawf.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtuiztvzxd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtwkvfvvgs.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtrsdurbwh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtwupyirrb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcvtbwsnu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtoinkxtbo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzbobpgkd.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtcnnrjgeg.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtpzbbxrpd.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtyyqyekhm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtxkyrflot.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gttkdwtxdf.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtukpffgal.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtvcibkxwz.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtunpvatry.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gtxxkudxgy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtzjewvqwd.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtckmtqcrh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtjpnrkqyr.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtqxnhdati.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtthubpzhf.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtosxfbwcx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gteurdulhq.html


<!-- 参考信息 -->