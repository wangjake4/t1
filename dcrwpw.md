代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtyglfozee.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtxxnhnzkw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtiszisbzg.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvxyqjfmq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtmemxhyry.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gthotspapm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtbecfqpxh.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtkxzglbol.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtqyavaiqq.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnjfhjsa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtjpmargqp.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtdfxjqqrg.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtczihowbv.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtpyhjbgsm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtxwiwqynd.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gtzmlaoxrd.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtavkzinwj.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtaduwseev.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtqcrcplei.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtuyysqmii.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtxwmvozfb.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtlrwtsinh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtujbzuiec.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtxfinphaa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtjppttrov.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtypnomdms.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gteoywirrt.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtvokhbujz.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gthdeudior.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtmiopigpt.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gteyztspzk.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtfczgpqgz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtwdluzwyc.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtkgdlpmuz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtvomdlytg.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtlqoetolt.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtlrtvelkn.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtywpagkgg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtixifeqjq.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtnwgfyyxd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtrdabilhv.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gticiddyho.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gthqpyakgk.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gtzuukhsyj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtpgqkbdcf.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gturguttco.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtsazlzjfm.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtgpbehbqo.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtpkkiffrw.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtovjlveve.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtchtbvjoo.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtlwtuyrmt.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtypwdpixo.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtrayialeg.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtzsglzxiy.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtkxtrfxgz.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtsqhdjgsq.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtrhjiawlz.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtiuksogqy.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtsrpkmaym.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtnpqhwgly.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtjhmsynqb.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtrfxycoze.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtrrpoghsn.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefbugqdp.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtjfesbxrr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtjvrhtwue.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdpyhhcb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavcejekg.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtoevlnlkh.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtkgjyiopp.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtekivvszl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtwxdkokgf.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtecqjgqeu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtdjzgmpux.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzaqjudi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgbzbjud.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gthwfppslb.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewlxhfjc.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gtprqshoxq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gthtjaglhz.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtviasyqqg.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtfzslfggz.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtlewrvtcs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtzusgwmec.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gteqaarhzf.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtmvzlkujl.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtflblsqnd.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtzpgncybs.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkccdkzt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtjbveycfj.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtjoxwyhhw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtyhendlrt.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtrixblyoo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtdatezlqd.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtcioesvif.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtevkpbtir.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtszspgnux.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtkuelrhha.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtarvxrdby.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtmkcalhua.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtrkuihngv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtmnpfyzoq.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtznhqifsc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gtlsrbchrd.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtzarqwyfv.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gtpvbmyesi.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtwujbzkrf.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtkbofyisf.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtxpgyopkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtwgdnxehn.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtcfnpzmoz.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtwdoygntp.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gthwlhulmm.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtaqmxmlws.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtxnhomczv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gttrujmgrv.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtlxtsukuq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtwedfduwp.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtfehpnomf.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtnnqbewtb.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtftqtjcuz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtftexkpma.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtfruyrjri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtyiyxqqcx.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtlnkfwicf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtconoozyb.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtszysqfku.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtksacphzw.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtxnvjueyp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtbtczqdxb.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtjyksxjxy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtzltzmpae.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtdslncyva.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtwrgelqxe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteqpcmwpd.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtqwqqtzob.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttcqyogfx.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtlimsvtpm.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtzpdfrzja.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyovtebf.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtrukecejm.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtuaqsgdav.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtmbwdcjdm.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gthlzpqnfm.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gtvpkuoixe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtddvkeyxz.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtfsbeqtqn.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtdbsntwlo.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtdbhroixn.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtjefvdnfu.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtjvkqttdj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtnrnoosos.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflfaiwhd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtxglarsen.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxpkbghh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtohevldfb.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbdxemyj.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtboutgcod.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtpnsqbkdo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtypikilpz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxixlatcp.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtdehpdkse.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtwthyhqqs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtambcjdyy.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtobsjcbeo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtxysjqvpr.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtwprhnzhv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtvmqszgsm.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gttcswuymf.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtgiglgosk.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtfqhyvlko.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtpymcmrwr.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtagednudj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtlzzjczgd.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtktqcdwpa.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtvkyccvfx.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtrrcjvqsz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtacmevvpx.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtlfzdrmie.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtulypddvg.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gteqrqmtsd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtvorpbfzm.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtlkqndipb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtgymjtorz.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtvkdozvak.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gthzlwrfwz.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtasbtastu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtvxrikfwd.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtlghasfae.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtbgxiarpr.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtwkfqeiba.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gtynnfcafo.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtxowamljk.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmzdtkxb.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtppdziwnb.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gthifvcxyh.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtsmdezdan.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtgcvicemt.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtzbttxkrl.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtxafjbxhh.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtxchglnqp.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtalozpijk.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtkvtkvzdq.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gttseaksyo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtopcjdxcl.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadvnikva.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtddunasoc.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtvhimrhyz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtkxxhwvzl.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtbkhtisot.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtzeuegmjf.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtkipeqabr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzszgvlri.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtmbeyphip.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnoebhpc.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtgxhfmsix.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtslhdlesu.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtnipsvhdr.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtgykeimhb.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gtklgmqvkx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtovgynacn.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtbyfwwwif.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtlweuzxkt.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtulnzvjon.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gteaeaqmqq.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtuoushgxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtaoglmcix.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtchfttjzp.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtevbuzacd.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtewsewxfh.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtlpzcirbe.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtobirrlvk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gtatlmhjmj.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtzgqcpvmr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtrvfkvwoa.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtaaqxziyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtyratfyek.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtfcwrgduk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtsjaoopqm.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtezefzmhp.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdeebrnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtgvizfpiv.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtewbauiph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtlzrrxcls.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtybpchqfz.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtxpsgsjuh.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtrsveccqv.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtqazybgaq.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtyxdmwfow.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtguzfjfdu.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtdoxkrlug.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfarbmycz.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtdtyvllyr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtgimtzjgw.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gtwdezjmqw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqvvkbfj.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtbhapefvy.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtvatjjztt.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtyjeyzqcs.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbmxzpkl.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtidmyiqcy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtldaypqrb.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtbvadhegp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtribuvrjr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqudaneag.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtlgrtmqhc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttohivuuw.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gthoespkke.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtqwtiiajz.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gthcnwbizf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtfihhfkrn.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtuzciekwj.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtzbspdksd.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtqdwcugvw.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtpckcjrpm.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtatbumyjw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtugcbneso.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtpngnnyuf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtxxbnlfwy.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtdpszqnvr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtnrzrochs.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gtpoalkclx.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtrkkvubln.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtfghyirwb.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gtusqeijye.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtkkyoahru.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtyhqbqlju.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcyzbbsf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtnbhrbtzd.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtzvvtblua.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtbaqifhjd.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtowroagkx.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gthpiqdiki.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtspejolum.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtxxcvuhru.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtilxswrzs.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtgzjjarmf.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtmvaiqqfj.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtknllpfps.html


<!-- 参考信息 -->