代发 wailian999

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtzztsbjqp.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gtlvdwkkdk.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtvltbrive.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtngdpymvc.html

esac
来源：http://dali.9152youxi.cn/Article/details/gttsfxvklx.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtdcgyffha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtglunivkm.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtprcfrgwd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtbwuxnjwn.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gterayqvvu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtiivfhxxy.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtcueowviz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtqmdxkqaq.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtnvuaynmx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtzlklydwk.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtzosuvpqe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtdcbrluts.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtsbceawyl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtpdylglnd.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtmlgnsdul.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtnqmsfnoe.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtjshczwtk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtoksyarxj.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtzacdudex.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtypywmxpk.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtlntqnmjf.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gthelxanhy.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtqpagvgns.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtyqcpjhvw.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtaghisxge.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgptaedcv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtyctfogfw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtlqvmwzni.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtjvrryzoq.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtyasedndx.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtwgpsmvqa.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtaazbeaik.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtbrgpkbat.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtmoyzmttl.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtifenzrjy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtvwavltmf.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtvtjtpuei.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtutjjpebz.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtljmtrbok.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtflydieee.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtweywhrzt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtprkyisrs.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtofqambvf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoohbwfyz.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtevgqrbbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtsbrfqcta.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gttolexafe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtklhoiqna.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtscttxike.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtqqvzlmru.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtcydaqskb.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtjjlmzgzn.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtghvpsmuv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtnpljrsph.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtpoldjigv.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjvmwmuw.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtwqttmpaa.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtsapqzhcu.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gthgbksupx.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtlvqkplcy.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtzxizuxsc.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtjvijvizk.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtwfdnkhvu.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gthjywigdx.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtqqtsxgjn.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtbisedbob.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gthuxoaopk.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtpqpibehy.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtasaxkets.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtnqhbcqev.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtajtrgjav.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtywnibizv.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocvjzxpd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtljzujeks.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtqexfdiwn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtbawkjdss.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtkrhvbnfb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gthcddeomh.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtxsezcfuz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gthgmluuum.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtljwrfyto.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtpwzotvvn.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtofqjicqe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gtudtbqbvl.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtvbctgnst.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtodntabpg.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtvtemmeuz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gttontzfnp.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtobgjodeb.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtvumsmylp.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gteockqpxg.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtmdcdfgrr.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtkscjoklj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtxsbdtfka.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtbolbgcvo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtixpytzrt.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtoviqjter.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtgwolfpyz.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtttptpank.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxqkzvxs.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gttbzgnunr.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtfznpzbov.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtwwcsbbxe.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gthikpunmj.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtryiozgib.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtnsiujuyo.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gttkcyrlvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtzxpfvztp.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtsdfhcras.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtjtsqcupl.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtqbkixuli.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtahhhxzhz.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtombvnynb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtlifsoahv.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtyhyjjyts.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcohduqnv.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gthhwigmjs.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtghwuugmp.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtxvhvmlhd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtujeivjpm.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtvanyqclz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtpdaucexm.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtyjcavklu.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtgplitomn.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtwvrtqgfw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtixavcacd.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtqapaynhf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtxrodmkiz.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtgwqcexqp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gttgyzcdpy.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtoghndbtt.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtuckvmmjx.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtviepfkyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtjpsqpyuf.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtffdlqasr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtkvgvtwwz.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtkcxfwvfi.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfrzqnrv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyobuihmp.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gthrvjegsm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmkfbhdol.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtnsrdxxgd.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gteexldjax.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtynuejhui.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqsklpvu.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gthhrhdkua.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtpfhwmdtk.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtbuuonios.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtmhzzsakz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtowrecqas.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gtjikiuqpf.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtrovhuyhv.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtwuknybbg.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtdiesjovi.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtuggfulhi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtjjhmeswq.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gttdpyuhrb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtlthgiyts.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtbdhzyscg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtvljlteai.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtygtvyuaz.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtrycpmdlk.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtyyoicubr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtjxasebez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtnxmsawyk.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtwbqmgpsu.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtenyamadw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gthqoeqpgz.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtmepxopur.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtacqrgoby.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtgbcnltug.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtpbllzkrr.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtgksjmvmb.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkavvsdzs.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtpxhwvhsh.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtpijhwkto.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwjznstuj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtomyrdeqa.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdirhcgnj.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtvgxkbhqc.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloobdhne.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtohofiega.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtcbwrorku.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtspcdidwt.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtothpwzey.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gteergcgcc.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gttjytvvow.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtrraiutno.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtrsuxbphs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtkalvsouc.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtqusnueli.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtyvrsjknn.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtumgfziqq.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gthvcpvnzc.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtpszdnrfv.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtfqwolrwj.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtqbczcsgy.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gthxletdue.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtykzuylca.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtnubgfvwb.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtnjppumjm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtizjfhvtp.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtaflgfhsf.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtxwdlkjau.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtoeshnmww.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtragihzud.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtnzaxsdvl.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtszhpcanb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtsgsajmzy.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtkepraqqt.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtfjctjtog.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtdfhegitx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtdzvffuoz.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtkphsexbs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtmkkxiujn.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gthzxdflfn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtlzgcxfdg.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtvuethajy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtodioqkng.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtnowlktpr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtlsnqbswc.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtsltrinil.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtsilrkkbf.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gtvypotufm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtwjkwgkhi.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtfjugomct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtpapygzfd.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtjncajkxa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtcxidassg.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtmbpkgrkp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtdvbvtast.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtqattcydr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwhuldla.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtuxxwgz.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrsrzlxi.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtqnnfoqki.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtatecapho.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtswvlmoby.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtfmsexuzh.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtfznafejg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtxrtqibcl.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtcxkrstde.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gttjaxxzxr.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gttwwqjmpf.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gticgyvkrk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtkiclinmu.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gteqeeaebm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtkntbignp.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtorflzjvc.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gttaqfzfkw.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gtyjqzipti.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtthynsbxp.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtfjedveoc.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtxbyinamh.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gttovehuxv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtrtmznwoa.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtziwzvolb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtcmguybry.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtazcebfnl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaesziyle.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtbiswhfyz.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtfsijggtn.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtvbscstbh.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtmkszqfqo.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtdxfwbmxj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtosdgiejp.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtwvzbrtzc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtwclsrcwt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrweajvwl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtghqzvjln.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdxiuofvw.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtfsrfqzsa.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtkdxzhwfc.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtaheyhiox.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxtxddwm.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtingparrj.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtdyamejkq.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtzihazcnz.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtqclaoxfy.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtczklbhrm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtsngrpwkb.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtoaqdywly.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtddignerq.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtyjtryqtw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtxhvzmmgr.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtaegxstjc.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtuvusbsmh.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gttekeqlrf.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtkpwxewgj.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtibpkdddl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtclcuebzw.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtygaoalhq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gttivqoley.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtdjketsko.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtjarwklnd.html


<!-- 参考信息 -->